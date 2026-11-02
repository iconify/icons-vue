<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f5blpn4vc"/><path class="x48gtebgo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sword-duotone-sharp" /></template>
<style>
.f5blpn4vc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17.293 2.293A1 1 0 0 1 18 2h3a1 1 0 0 1 1 1v3c0 .265-.105.52-.293.707l-11 11a1 1 0 0 1-1.414 0l-3-3a.997.997 0 0 1 0-1.414Z");
}

.ft5dv1b6b {
  fill: none;
}

.x48gtebgo {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 14L18 3h3v3L10 17m-5-5l7 7m-4-3l-4 4m-1-1l2 2");
}

</style>
