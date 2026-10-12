<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="svh75n4ci"/><rect class="e6h98mbed"/><path class="ebqnhw7ht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:well-bucket" /></template>
<style>
.e6h98mbed {
  width: 15.5px;
  height: 4.75px;
  x: 4.25px;
  y: 16.5px;
  rx: 1px;
}

.ebqnhw7ht {
  d: path("M4.25 18.88h15.5M12 16.5v2.38");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.svh75n4ci {
  d: path("M2.75 8L12 3l9.25 5M5.5 6.51v9.99m13-9.99v9.99M5.5 9h13M12 9v2.5m-1.75 0h3.5q.5 0 .36.48l-.47 1.54Q13.5 14 13 14h-2q-.5 0-.64-.48l-.47-1.54q-.14-.48.36-.48");
}

</style>
