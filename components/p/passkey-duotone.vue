<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b5_xu1w1b"/><path class="i6ovhybbp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:passkey-duotone" /></template>
<style>
.b5_xu1w1b {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3.393 5.053a5.001 5.001 0 1 1 9.213 3.896a5.001 5.001 0 0 1-9.213-3.896M13 22H3a1 1 0 0 1-1-1a8 8 0 0 1 .45-2.668C3.295 15.937 5.357 14.001 8 14c2.643.001 4.705 1.937 5.55 4.332c.301.857.453 1.76.45 2.668a1 1 0 0 1-1 1");
}

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

</style>
