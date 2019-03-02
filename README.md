# How-to-Present-Coding-Problem-in-Discord

## Code Block

format:
```
    ```alias(optional)
       code
    ```
```

for example, jsx code
```
```jsx
class List extends Component {
    render() {
        return (
            <Subscribe to={[ToDoContainer]}>
                {(toDo) => (
                    <>
                        {toDo.filteredList().map(({ text, done }, index) => {
                            return (
                                <ListItem
                                    // dynamically generate the list items
                                    key={index}
                                    index={index}
                                    text={text}
                                    done={done}
                                    toDo={toDo}
                                />
                            )
                        })}
                    </>
                )}
            </Subscribe>
        )
    }
}

export default List
```
```
