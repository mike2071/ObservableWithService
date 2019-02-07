# ObservableWithService

##Instructions

### app.service.ts
Opne the app.service.ts file and study the code to see how we have set up an observable by using an "EventEmmitter".

Notice the function there that uses the event emmiter to emit a stream on dates in the "setInterval" function, this is just to provide us with a stream of data so we can subscribe to our observable and see some data.

### app.component.ts
open up the app.component.ts notice we have injected our service via the constructor.

Then we have called implemented the "ngOnInit" and we subscribe to our observable in it
