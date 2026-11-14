<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j3yijrbyb"/><path class="ca8t8abxk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:radiologist" /></template>
<style>
.ca8t8abxk {
  d: path("M10.25 6.5C7.5 6.5 5.5 7.5 5.5 9m4.75-2.5C13 6.5 15 7.5 15 9m-4.75.5c-2.75 0-4.75 1-4.75 2.5m4.75-2.5C13 9.5 15 10.5 15 12m-4.75.5c-2.25 0-3.75.75-3.75 2m3.75-2c1.833 0 3.169.498 3.6 1.358m2.4 1.892a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM14.5 21.5c0-2 1.5-3 3.5-3s3.5 1 3.5 3");
}

.j3yijrbyb {
  d: path("M12.8 18H2.5V2.5H18v8.7M10.25 5v10.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
