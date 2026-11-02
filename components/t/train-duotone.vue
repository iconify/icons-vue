<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ck0dipbtf"/><path class="djulzlbey"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:train-duotone" /></template>
<style>
.ck0dipbtf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 18a3 3 0 0 1-3-3V7c0-1.039.578-1.992 1.293-2.707l1-1C7.008 2.578 7.961 2 9 2h6c1.039 0 1.992.578 2.707 1.293l1 1C19.422 5.008 20 5.961 20 7v8a3 3 0 0 1-3 3Z");
}

.djulzlbey {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 17H7a2 2 0 0 1-2-2V7c0-.64.36-1.36 1-2l1-1c.64-.64 1.36-1 2-1h6c.64 0 1.36.36 2 1l1 1c.64.64 1 1.36 1 2v8a2 2 0 0 1-2 2zm-4 0l-2 4m10-4l2 4M5 10h14M9 14h.01M15 14h.01");
}

.ft5dv1b6b {
  fill: none;
}

</style>
