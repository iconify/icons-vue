<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="nx5d-bc1s"><path class="i1sg4lbhw"/><path class="r0jd0fpwr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:qtcon" /></template>
<style>
.i1sg4lbhw {
  d: path("M20.084 5.164a2.033 2.033 0 0 0-1.894-2.16a2.026 2.026 0 0 0-2.132 1.917c-.121 2.058-.998 4.038-2.361 5.777L10.224 7.22a8.15 8.15 0 0 0 1.081-3.157C11.377 3.477 10.89 3 10.302 3H4.075C3.482 3 3 3.482 3 4.078v6.238c0 .59.476 1.078 1.06 1.006a8.1 8.1 0 0 0 3.194-1.11l3.402 3.409c-1.98 1.455-4.135 2.358-5.873 2.58a2.034 2.034 0 0 0-1.75 2.28a2.02 2.02 0 0 0 2.252 1.771c2.7-.343 5.702-1.712 8.269-3.728l3.85 3.858A2.105 2.105 0 0 0 21 18.89c0-.56-.222-1.097-.617-1.493l-3.807-3.814c1.913-2.32 3.319-5.19 3.508-8.42");
}

.nx5d-bc1s {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
}

.r0jd0fpwr {
  d: path("M11.487 13.044q-.39.322-.79.615l2.88 2.885q.593-.462 1.153-.97a19 19 0 0 0 1.828-1.9c-.642-.58-1.483-1.164-2.824-1.164c-.984 0-1.712.243-2.247.534");
}

</style>
