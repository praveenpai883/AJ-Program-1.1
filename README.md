# AJ-Program-1.1
<!DOCTYPE html>
<html>
<head>
 <title>Full Name Program</title>
 <script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.9/angular.min.js"> 
 </script>
</head>
<body>
 <div ng-app="myApp" ng-controller="myCtrl">
 <h1>Full Name Program</h1>
 <input type="text" ng-model="firstName" placeholder="Enter First Name">
 <input type="text" ng-model="lastName" placeholder="Enter Last Name">
 <br>
 Full Name: {{firstName + " " + lastName}}
 </div>
 <script>
var app = angular.module("myApp", []);
app.controller("myCtrl", function($scope) {
$scope.firstName = "Rajender";
 $scope.lastName = "Tilak";
});
 </script>
</body>
</html>
