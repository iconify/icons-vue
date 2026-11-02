<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xx2k2ktcb"/><path class="w7cqvmbfs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-outgoing-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.w7cqvmbfs {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 5a2 2 0 0 1 2-2h3c.995 0 1.8.403 2 1l1 3c.153.46-.234 1.234-1 2l-1 1a1.414 1.414 0 0 0 0 2l3 3a1.414 1.414 0 0 0 2 0l1-1c.766-.766 1.54-1.153 2-1l3 1c.597.2 1 1.005 1 2v3a2 2 0 0 1-2 2C10.163 21 3 13.837 3 5m14-2h4v4m0-4l-6 6");
}

.xx2k2ktcb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 3h3c.698 0 1.747.244 2 1l1 3c.212.639-.593 1.592-1 2l-1 1a1.415 1.415 0 0 0 0 2l3 3a1.415 1.415 0 0 0 2 0l1-1c.408-.407 1.361-1.212 2-1l3 1c.756.253 1 1.302 1 2v3a2 2 0 0 1-2 2C10.163 21 3 13.837 3 5a2 2 0 0 1 2-2");
}

</style>
