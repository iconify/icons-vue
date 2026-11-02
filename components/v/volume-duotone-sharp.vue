<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="iiqqoq0_z"/><path class="sudosfteo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iiqqoq0_z {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m11 20l-4-4H3V8h4l4-4Z");
}

.sudosfteo {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 4v16l-4-4H3V8h4z");
}

</style>
