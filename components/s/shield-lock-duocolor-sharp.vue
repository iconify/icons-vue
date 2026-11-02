<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u1tfz0meq"/><path class="qyxqzrb2b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-lock-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qyxqzrb2b {
  d: path("M12 3h8v7c0 5.5-3.5 9-8 11c-4.5-2-8-5.5-8-11V3z");
}

.u1tfz0meq {
  stroke-opacity: 0.4;
  d: path("M9 10h6v4H9Zm1 0V9a2 2 0 1 1 4 0v1");
}

</style>
