<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="eugq6wbiy"/><path class="q5eabb2fz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-edit-corner-duotone" /></template>
<style>
.eugq6wbiy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 6c.326-.651 1.15-1.999 2-2h10c.85.001 1.674 1.349 2 2l1 2H4Zm8 15v-3l5-5l3 3l-5 5Z");
}

.ft5dv1b6b {
  fill: none;
}

.q5eabb2fz {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 8v10a2 2 0 0 0 2 2h2M4 8l1-2c.613-1.226 1.387-2 2-2h10c.613 0 1.387.774 2 2l1 2M4 8h16m-7 13v-3l5-5l3 3l-5 5Z");
}

</style>
