# data-sharing-between-angular-components
In Angular, @Input() and @Output() decorators are used for sharing data between components.

@Input() is used to pass data from a parent component to a child component. The parent component passes the data as a property binding in the child component's selector. In the child component, the @Input() decorator is used to declare the property that receives the data.

@Output() is used to pass data from a child component to a parent component. The child component emits the data through an event using the EventEmitter class. In the parent component, the @Output() decorator is used to declare the event handler function that receives the emitted data.

Using these decorators, components can share data and communicate with each other, enabling more complex and interactive applications.
![Sharing data in Angular components](https://user-images.githubusercontent.com/114358610/224474671-8873b4f4-3839-46b3-abca-3e306d9d04d7.png)
