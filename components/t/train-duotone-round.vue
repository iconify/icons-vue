<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="efeijebyn"/><path class="o0ul6jb4v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:train-duotone-round" /></template>
<style>
.efeijebyn {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 18a3 3 0 0 1-3-3V8c0-1.317.335-2.748 1.293-3.707l1-1C7.252 2.335 8.683 2 10 2h4c1.317 0 2.748.335 3.707 1.293l1 1C19.665 5.252 20 6.683 20 8v7a3 3 0 0 1-3 3Z");
}

.ft5dv1b6b {
  fill: none;
}

.o0ul6jb4v {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 17H7a2 2 0 0 1-2-2V8c0-1.28.36-2.36 1-3l1-1c.64-.64 1.72-1 3-1h4c1.28 0 2.36.36 3 1l1 1c.64.64 1 1.72 1 3v7a2 2 0 0 1-2 2zm-4 0l-2 4m10-4l2 4M5 10h14M9 14h.01M15 14h.01");
}

</style>
