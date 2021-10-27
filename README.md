# Node.js-numbers-array
var Calculator = {
	average: function() {
 		return [].reduce.call(arguments, function(sum, argument) {
 			return sum + argument;
 		}, 0) / arguments.length || 0;
 	}
};
