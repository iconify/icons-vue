<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gaq6f11lf"/><path class="ond4guogw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:yacht-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gaq6f11lf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 8a3 3 0 0 1 3-3h7c.379 0 .725.214.894.553l3 6A1 1 0 0 1 17 13H5a1 1 0 0 1-1-1Z");
}

.ond4guogw {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m4 17l-1-5h18l-1 5M5 12V8a2 2 0 0 1 2-2h7l3 6M7 6V3M2 20c.5.5 1 1 2 1c2 0 2-2 4-2s2 2 4 2s2-2 4-2s2 2 4 2c1 0 1.5-.5 2-1M12 9h.01");
}

</style>
