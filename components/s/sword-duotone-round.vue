<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xuoy9ibxm"/><path class="dg6f8u7wi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sword-duotone-round" /></template>
<style>
.dg6f8u7wi {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 14L17 4c.64-.64 1.72-1 3-1h1v1c0 1.28-.36 2.36-1 3L10 17m-5-5l7 7m-4-3l-4 4m-1-1l2 2");
}

.ft5dv1b6b {
  fill: none;
}

.xuoy9ibxm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16.293 3.293C17.252 2.335 18.683 2 20 2h1a1 1 0 0 1 1 1v1c0 1.317-.335 2.748-1.293 3.707l-10 10a1 1 0 0 1-1.414 0l-3-3a.997.997 0 0 1 0-1.414Z");
}

</style>
