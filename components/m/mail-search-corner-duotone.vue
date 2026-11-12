<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kz8mdd50t"/><path class="b2zeksbry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-search-corner-duotone" /></template>
<style>
.b2zeksbry {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 19H5a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v4M4 6l4 4c.64.64 1.36 1 2 1h4c.64 0 1.36-.36 2-1l4-4m-5 11a2 2 0 1 0 4 0a2 2 0 0 0-4 0m4 2l2 2");
}

.ft5dv1b6b {
  fill: none;
}

.kz8mdd50t {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 12h-8a.997.997 0 0 0-1 1v6a1 1 0 0 1-1 1H5a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v4a1 1 0 0 1-1 1");
}

</style>
