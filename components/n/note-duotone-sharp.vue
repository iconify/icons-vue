<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bkit9ltow"/><path class="ge5m_ub4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-duotone-sharp" /></template>
<style>
.bkit9ltow {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20 3a1 1 0 0 1 1 1v9c0 .265-.105.52-.293.707l-7 7A1 1 0 0 1 13 21H4a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1Zm-7 10v6l6-6Z");
}

.ft5dv1b6b {
  fill: none;
}

.ge5m_ub4c {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 20H4V4h16v9m0 0l-7 7m0 0v-7h7");
}

</style>
