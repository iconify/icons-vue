<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d1-_fmbch"/><path class="xl7_pw62p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:masks-theater-duotone-sharp" /></template>
<style>
.d1-_fmbch {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m9.86 4.775l9.848-1.737l1.216 6.894a5 5 0 0 1-4.056 5.792a5 5 0 0 1-5.792-4.056Z");
}

.ft5dv1b6b {
  fill: none;
}

.xl7_pw62p {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11.076 11.668L9.86 4.775l9.849-1.737l1.215 6.894a5 5 0 0 1-9.848 1.736m1.495 6.36a5.002 5.002 0 0 1-9.495-2.896l1.216-6.894l3.233.57m5.81-1.6h.01m3.93-.695h.01m-3.428 3.65a2.267 2.267 0 0 0 3.939-.695M6.725 11.713h.01m-.705 3.94a2.267 2.267 0 0 1 3.94.694");
}

</style>
