# Hotel-Management
Created a simple application using Spring Initializer With required depencdencies that manages Hotel App of an organization i.e., An Admin can add users, view list of users, get complete details of a user by Id, Delete user and update user.

## Frame Work And Language
* Spring Boot
* Java-17

## Data Flow
* ### Model
   #### HotelRoom
        roomid
        roomnumber
        roomtype
        roomprice
        roomstatus
   #### Type  
          AC
          NON_AC
          DELUXE       

* ### Controller
  #### RoomController
        rooms 
        room
        room/{id}
        room/{id}/exists
        rooms/count
        room/{id}/{type}
        rooms/status/{status}
        rooms/status/{status}/type/{type}
        rooms/status/{status}/type/{type}/priceRange
        rooms/type/{roomType}
        rooms/type1/{roomType1}/type2/{roomType2}
* ### Service
  #### RoomService
        getAllRooms
        addRooms
        getRoomById
        checkRoomExists
        getTotalRooms
        deleteRoomById
        addRoms 
        updateRoomById 
        getRoomsByStatus  
        getRoomsByStatusAndType 
        getRoomsByStatusAndTypeAndPrice
        getRoomsByTypeAndPriceSortedDesc
        getBudgetedAcOrNonAC
 * ### Repository
   #### IRoomRepo 
        findByRoomStatus
        findByRoomStatusAndRoomType
        findByRoomStatusAndRoomTypeAndRoomPriceGreaterThanAndRoomPriceLessThan       
        
        findByRoomTypeOrderByRoomPriceDesc
        getAllRoomById

## Data Base 
   * H2 Data Base        
## Data Structure
* String
* Integer 
* Boolean 

## Author

- [@Rudra Pratap Singh](https://github.com/rudrapratapsingh2000)

