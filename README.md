# Implement a calendar widget
Write an html file that contains your JavaScript, HTML and CSS to paint an array of events on a calendar. Each event has the following format.
```
var event = {
    “id”: “<event id goes here>”,
    “name”: “<event name goes here>”,
    “startTime”: “start time”, // format example - “Jan/15/2018 10:00 AM PST”
    “endTime”: “end time”
}
```

You must have a JavaScript function paintCalender(events) executable in global scope. It must take the array of events as argument. Each call to paintCalendar must remove any existing events in the calendar and paint the events passed in as argument. Test that this works in the browser console. The paintCalendar function will be used to test your code! Please try it out in the browser console before you turn in your solution.


##### Please note:
Name your file *calendar.html*.
Send it over to the recruiter when you are done within 5 hours of receiving it.
* Assume that the events are at least 1 hour long. Assume that events begin only at the start of an hour. You don’t have to support events that start, for example, at 1:30 PM.
* Assume that events don’t collide.
* Assume that all events occur between Jan/14/2018 and Jan/20/2018, both dates included.
* Your calendar must show a weekly view (one column per day), similar to google calendar view by week. The calendar must take up 100% of the browser width and height with reasonable margin and/or padding as you see fit.
* If an invalid event is passed (missing name, startTime, endTime etc), silently ignore the event and log the erroneous event to the browser’s console.
* When an event on the calendar is clicked, you must log the event name and duration to the browser console.
* Use of third party libraries like moment.js, date.js is not allowed. You may use jQuery if you prefer.
* **Clearly state any other assumptions you may make**


##### Rendered Result
see https://robert-kurcina.github.io/calendar-test/
