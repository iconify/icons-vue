<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kkv-c4rbd"/><path class="ijr-zmf5r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-embassy" /></template>
<style>
.ijr-zmf5r {
  d: path("M9.5 21v-4.5h5V21");
}

.kkv-c4rbd {
  d: path("M3.5 11h17v10h-17Zm8.5 0V2.5m0 0h6l-1.5 2.25L18 7h-6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
