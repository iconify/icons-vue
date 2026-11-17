<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jxqef6byg"/><path class="tbrw9cb0i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-flame-alt-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jxqef6byg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m7.333 11.333l-2.724 2.724a.388.388 0 0 1-.653-.359l.827-3.722A.803.803 0 0 0 4 9a.65.65 0 0 1-.594-.914l1.909-4.294A1.33 1.33 0 0 1 6.533 3H9a.773.773 0 0 1 .672 1.158L8.328 6.509A.772.772 0 0 0 9 7.667h.667a.552.552 0 0 1 .39.942Zm7.912 8.995c-4.187-4.05-1.3-7.583 1.165-10.601q.296-.361.59-.727q.294.366.59.727c2.465 3.018 5.352 6.551 1.165 10.601c1.133-1.18 1.26-2.371.364-3.736a6 6 0 0 0-.416-.561c-.51-.621-1.1-1.17-1.703-1.698c-.603.528-1.193 1.077-1.703 1.698a6 6 0 0 0-.416.561c-.896 1.365-.769 2.556.364 3.736");
}

.tbrw9cb0i {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.333 11.333L4.61 14.057c-.274.275-.737.02-.653-.359l.827-3.722A.802.802 0 0 0 4 9a.65.65 0 0 1-.594-.914l1.909-4.294A1.33 1.33 0 0 1 6.533 3H9c.594 0 .967.642.672 1.158L8.328 6.509A.774.774 0 0 0 9 7.667h.667c.492 0 .738.595.39.942zM16 21c-5.667-4.667-1.667-8.667 1-12c2.667 3.333 6.667 7.333 1 12Zm0 0c-3-2.333-1.667-4.333 1-6.667c2.667 2.334 4 4.334 1 6.667");
}

</style>
