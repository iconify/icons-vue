<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="c0wy7vqde"/><path class="iphxmvb_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-off-duotone" /></template>
<style>
.c0wy7vqde {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13 5c.369-.369 1 .262 1 1v2l-2-2Zm0 14l-2-2c-.528-.527-1.227-1-2-1H8a2.003 2.003 0 0 1-2-2v-4a2.003 2.003 0 0 1 2-2l6 6v4c0 .738-.631 1.369-1 1");
}

.ft5dv1b6b {
  fill: none;
}

.iphxmvb_n {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 8a2 2 0 0 0-2 2v4a2 2 0 0 0 2 2h1c.64 0 1.36.36 2 1l2 2c.369.369 1-.262 1-1v-4m0-6V6c0-.738-.631-1.369-1-1l-1 1M2 2l20 20");
}

</style>
