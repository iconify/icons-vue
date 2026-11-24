<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u5x_79dbp"/><path class="heujh0b5s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-edit-corner-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.heujh0b5s {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 8v12h4M4 8l2-4h12l2 4M4 8h16m-7 13v-3l5-5l3 3l-5 5Z");
}

.u5x_79dbp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 4h12l2 4H4Zm7 17v-3l5-5l3 3l-5 5Z");
}

</style>
