<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="i5xcnx86s"/><path class="j8wmmb73o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:soil-layers-sharp" /></template>
<style>
.i5xcnx86s {
  d: path("M2.75 9.5h18.5v11.75H2.75z");
}

.j8wmmb73o {
  d: path("M2.75 13.25c2.25 0 2.25-1 4.5-1s2.25 1 4.75 1s2.25-1 4.5-1s2.5 1 4.75 1m-18.5 4c2.25 0 2.25-1 4.5-1s2.25 1 4.75 1s2.25-1 4.5-1s2.5 1 4.75 1M12 9.5v-4m0 .5c0-2 1.25-3.25 3.5-3.25c0 2-1.25 3.25-3.5 3.25Zm0 1c0-1.75-1.1-2.75-3-2.75C9 6 10.1 7 12 7Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
