<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h7d5gfb4q"/><path class="jtg1620ro"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:megaphone-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h7d5gfb4q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16.553 4.106c1.12-.56 2.457-.597 3.583-.034c.534.267.996.658 1.328 1.154C21.816 5.753 22 6.367 22 7v8c0 .633-.184 1.247-.536 1.774a3.44 3.44 0 0 1-1.328 1.154c-1.126.563-2.463.526-3.583-.034l-6-3A1 1 0 0 1 10 14V8c0-.379.214-.725.553-.894Z");
}

.jtg1620ro {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m11 8l6-3c1.838-.919 4 .162 4 2v8c0 1.838-2.162 2.919-4 2l-6-3zm0 0H6a3 3 0 0 0 0 6h5m-6 0v5a2 2 0 1 0 4 0v-5");
}

</style>
