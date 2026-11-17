<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="im3xyseay"/><path class="n6r-f2kif"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-flame-alt-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.im3xyseay {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5.667 3h4.666L7.667 7.667H11L3.667 15L5 9H3Zm9.578 17.328c-4.187-4.05-1.3-7.583 1.165-10.601q.296-.361.59-.727q.294.366.59.727c2.465 3.018 5.352 6.551 1.165 10.601c1.133-1.18 1.26-2.371.364-3.736a6 6 0 0 0-.416-.561c-.51-.621-1.1-1.17-1.703-1.698c-.603.528-1.193 1.077-1.703 1.698a6 6 0 0 0-.416.561c-.896 1.365-.769 2.556.364 3.736");
}

.n6r-f2kif {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.667 3h4.666L7.667 7.667H11L3.667 15L5 9H3zM16 21c-5.667-4.667-1.667-8.667 1-12c2.667 3.333 6.667 7.333 1 12Zm0 0c-3-2.333-1.667-4.333 1-6.667c2.667 2.334 4 4.334 1 6.667");
}

</style>
