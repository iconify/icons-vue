<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w-02dghmi"/><path class="g0ray3b-f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:raccoon-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g0ray3b-f {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6c1.5 0 2.5-.2 3-1c.8-1.4 1.8-2 3-2c1.5 0 2 1 2 3c0 1.5 1 2.5 1 4v7h-2c-1 2.5-3.5 4-7 4s-6-1.5-7-4H3v-7c0-1.5 1-2.5 1-4c0-2 .5-3 2-3c1.2 0 2.2.6 3 2c.5.8 1.5 1 3 1m-3 6h.01M15 12h.01M12 18h.01M12 10c1-.7 2-1 3-1q3 0 3 3c0 1.7-.8 3-2 3h-1c-1.4 0-2.4-.8-3-2m0-3c-1-.7-2-1-3-1q-3 0-3 3c0 1.7.8 3 2 3h1c1.4 0 2.4-.8 3-2");
}

.w-02dghmi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 5c.666-1.165 1.599-1.999 3-2c1.5 0 2 1 2 3c0 1.5 1 2.5 1 4v7h-2c-1.161 2.897-4.065 3.999-7 4c-2.935-.001-5.839-1.103-7-4H3v-7c0-1.5 1-2.5 1-4c0-2 .5-3 2-3c1.401.001 2.334.835 3 2c.5.8 1.5 1 3 1s2.5-.2 3-1");
}

</style>
