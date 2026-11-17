<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="equ6t3nfd"/><path class="xpasmtb2f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tree-palm-duotone" /></template>
<style>
.equ6t3nfd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m12 8l-7 8a7.52 7.52 0 0 1 6.338-7.926L3 9a4.917 4.917 0 0 1 9-1m7 8l-7-8a4.918 4.918 0 0 1 9 1l-8.338-.926A7.52 7.52 0 0 1 19 16");
}

.ft5dv1b6b {
  fill: none;
}

.xpasmtb2f {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 8C9.875 4.211 4.241 4.837 3 9Zm9 1c-1.241-4.163-6.875-4.789-9-1Zm-9-1a7.52 7.52 0 0 0-7 8Zm7 8a7.52 7.52 0 0 0-7-8Zm-7 5V8");
}

</style>
