<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gkyj08y5a"/><path class="i467aemlx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shipping-port-sharp" /></template>
<style>
.gkyj08y5a {
  d: path("M3.75 11.5h17.5l-.47.88l-1.56 2.99l-.47.88H5.25l-.47-.88l-1.56-2.99l-.47-.88z");
}

.i467aemlx {
  d: path("M4.5 11.5V8H10v3.5Zm8.5 0V6.25h5.5v5.25ZM3.25 20c1.25 0 1.25-.75 2.5-.75S7 20 8.25 20s1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
