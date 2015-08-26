## ng-regex Angular Directive

### <a href="http://codepen.io/zerohouse/pen/MwNxeR" target="_blank">Demo</a>

#### example
    <input ng-regex="\w{2,}" message="waring: too short" ng-model="name">
    
    
#### example2
    <input ng-regex="emailRegex" message="waring: email not valid" ng-model="email">


    $scope.emailRegex = new Regex('...');