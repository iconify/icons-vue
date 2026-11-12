<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jcap-jutn"/><path class="bup-vfb2v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-edit-duotone" /></template>
<style>
.bup-vfb2v {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 15v-3l8-8a1.414 1.414 0 0 1 2 0l1 1a1.414 1.414 0 0 1 0 2l-8 8zm6-9l3 3M3 21l3-3l3 3m4 0h8");
}

.ft5dv1b6b {
  fill: none;
}

.jcap-jutn {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 12c0-.265.105-.52.293-.707l8-8a2.414 2.414 0 0 1 3.414 0l1 1a2.414 2.414 0 0 1 0 3.414l-8 8A1 1 0 0 1 12 16H9a1 1 0 0 1-1-1Z");
}

</style>
