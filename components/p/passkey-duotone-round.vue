<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s54t6nbeq"/><path class="i6ovhybbp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:passkey-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i6ovhybbp {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 7a4 4 0 1 0 8 0a4 4 0 0 0-8 0M3 21c0-3.314 2.239-6 5-6s5 2.686 5 6m6-9v-2h-3m3 2v5m0-5h-3m1 7a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

.s54t6nbeq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 7a4 4 0 1 1 8 0a4 4 0 0 1-8 0M3 21c0-3.314 2.239-6 5-6s5 2.686 5 6Z");
}

</style>
