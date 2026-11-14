<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h60f0sbox"/><path class="tz6diqz3l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:terrarium-bottle" /></template>
<style>
.h60f0sbox {
  d: path("M10.25 2.5h3.5v5c3.75 1.25 5.75 4.25 5.75 7.5c0 4-3 6.5-7.5 6.5S4.5 19 4.5 15c0-3.25 2-6.25 5.75-7.5ZM12 18.75V13");
}

.tz6diqz3l {
  d: path("M12 14c0-1.75 1.25-2.75 3-2.75C15 13 13.75 14 12 14Zm0 1.5c0-1.75-1.25-2.75-3-2.75c0 1.75 1.25 2.75 3 2.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
