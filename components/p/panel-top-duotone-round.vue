<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jarms2bkf"/><path class="jmix4ccgc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:panel-top-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jarms2bkf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 10a1 1 0 0 1-1-1V8a5 5 0 0 1 5-5h8a5 5 0 0 1 5 5v1a1 1 0 0 1-1 1Z");
}

.jmix4ccgc {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 8a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4v8a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4Zm0 1h16");
}

</style>
