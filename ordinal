const nth = function(d) {
    if (d > 3 && d < 21) return 'th';
    switch (d % 10) {
        case 1:  return "st";
        case 2:  return "nd";
        case 3:  return "rd";
        default: return "th";
    }
};

const dateObj = new Date();
const date = dateObj.getDate();
const month = ["January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"][dateObj.getMonth()];
const year = dateObj.getFullYear();

var dateString = date+nth(date)+' '+month+' '+year;
