<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e99hrhp6j"/><path class="n53h-tcju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-pin-corner-duotone-sharp" /></template>
<style>
.e99hrhp6j {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20 4v4H8v12H4V4Zm-5 9h4v3l2 2h-8l2-2Z");
}

.ft5dv1b6b {
  fill: none;
}

.n53h-tcju {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 20H4V4h16v4m-5 5h4v3l2 2h-8l2-2zm-1 0h6m-3 5v3");
}

</style>
