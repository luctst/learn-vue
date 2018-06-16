# learn-vue
Become a VueJs expert

## Style
Three ways of styles your element with VueJs:
- **Object:** - You can use `:class="{className: condition}"`, where the key is the name of your class and the value is the condition to apply this class.
- **Class name:** - You can use `:class="className"`, where the className is the name of a property which correspond to a name in your css file.
- **Array:** - You can use `:class="[firstClassName, secondClassName,..]"`, where the differents index correspond to different properties.
> **Note:** - You can also call a function with this methods above.