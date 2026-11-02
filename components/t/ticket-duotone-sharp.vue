<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ms_3c9dqa"/><path class="rr2p1mbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ticket-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ms_3c9dqa {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 6v3a3 3 0 1 0 0 6v3H3v-3a3 3 0 1 0 0-6V6Z");
}

.rr2p1mbnq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 9V6H3v3a3 3 0 0 1 0 6v3h18v-3a3 3 0 0 1 0-6m-7-3v12");
}

</style>
