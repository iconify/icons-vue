<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kiry42bvh"/><path class="lh39odbug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:penguin-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kiry42bvh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 8v2.74c.697 1.303 1 2.789 1 4.26a6.6 6.6 0 0 1-.627 2.842a6.6 6.6 0 0 1-1.725 2.232C16.086 21.401 14.027 22 12 22s-4.086-.599-5.648-1.926a6.6 6.6 0 0 1-1.725-2.232A6.6 6.6 0 0 1 4 15c0-1.471.303-2.957 1-4.26V8c0-2.731 1.458-4.776 4.077-5.595C10.02 2.11 11.014 2 12 2s1.98.11 2.923.405C17.542 3.224 19 5.269 19 8");
}

.lh39odbug {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3c4 0 6 2 6 5v3c.7 1.2 1 2.6 1 4c0 3.5-3 6-7 6s-7-2.5-7-6c0-1.4.3-2.8 1-4V8c0-3 2-5 6-5m6 8l3 4M6 11l-3 4m7-8h.01M14 7h.01M11 10h2l-1 1Zm-5 1c2 1 3 3 3 5c0 1.5 1 2 3 2s3-.5 3-2c0-2 1-4 3-5");
}

</style>
