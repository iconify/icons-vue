<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t2x2sobde"/><path class="vj0o1h0mc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:navigation-alt-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.t2x2sobde {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 18c.369 1.107-.262 2.369-1 2l-4-2l-4 2c-.738.369-1.369-.893-1-2l4-12a1.054 1.054 0 0 1 2 0Z");
}

.vj0o1h0mc {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m15 12l2 6c.369 1.107-.262 2.369-1 2l-4-2l-4 2c-.738.369-1.369-.893-1-2l4-12c.32-.961 1.68-.961 2 0z");
}

</style>
