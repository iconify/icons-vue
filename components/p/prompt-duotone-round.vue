<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="da7423ruy"/><path class="xmg1kynso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:prompt-duotone-round" /></template>
<style>
.da7423ruy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20 12c-2.998.002-4.998 2.002-5 5c-.002-2.998-2.002-4.998-5-5c2.998-.002 4.998-2.002 5-5c.002 2.998 2.002 4.998 5 5");
}

.ft5dv1b6b {
  fill: none;
}

.xmg1kynso {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 4h4M4 20h4M6 4v16m9-13c0 3 2 5 5 5c-3 0-5 2-5 5c0-3-2-5-5-5c3 0 5-2 5-5");
}

</style>
