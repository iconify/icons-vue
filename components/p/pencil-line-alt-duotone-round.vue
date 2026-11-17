<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ep_dm2bsl"/><path class="s2-bnmbnv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-line-alt-duotone-round" /></template>
<style>
.ep_dm2bsl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 16L14 6a2.828 2.828 0 1 1 4 4L8 20H4Z");
}

.ft5dv1b6b {
  fill: none;
}

.s2-bnmbnv {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 20v-4L14 6a2.828 2.828 0 1 1 4 4L8 20zm4 0h12");
}

</style>
