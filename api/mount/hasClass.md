# hasClass(className)

Check if wrapper DOM node has a class name. Returns a boolean.

### Arguments

className (String): class name to assert element contains.

### Returns

(Boolean): true if element contains class. False if not.

## Example

```js
import { mount } from 'avoriaz';
import Foo from './Foo.vue';

const wrapper = mount(Foo);
expect(wrapper.hasClass('bar')).to.equal(true);
```