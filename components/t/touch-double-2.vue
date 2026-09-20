<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o35_5abth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:touch-double-2" /></template>
<style>
.o35_5abth {
  fill: currentColor;
  d: path("M10.412 21q-.547 0-1.04-.215q-.495-.214-.824-.668l-4.917-6.283l.323-.322q.31-.31.755-.356q.445-.047.841.182l2.508 1.54V8.193q0-.194.143-.347t.357-.153q.194 0 .347.153t.153.347v3.789h2.269V6.519q0-.194.143-.347t.357-.153q.194 0 .347.153t.153.347v5.462h4.288q.981 0 1.683.702T19 14.366v3.288q0 1.406-.983 2.376t-2.363.97zM4.344 9.158q-.055-.237-.065-.473q-.01-.237-.01-.493q0-2.573 1.797-4.383Q7.864 2 10.462 2q2.573 0 4.373 1.81t1.8 4.382q0 .218-.038.551l-.038.334l-.98-.11l.028-.287q.028-.288.028-.488q0-2.151-1.511-3.672T10.462 3Q8.285 3 6.777 4.52T5.269 8.192v.4q0 .2.05.4z");
}

</style>
