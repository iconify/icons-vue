<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bq0pqg4nx"/><path class="dubabk8wl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-landing-side-duotone-round" /></template>
<style>
.bq0pqg4nx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8.553 5.658L9.882 3a1.794 1.794 0 0 1 2.586-.71c.289.188.514.458.648.776l2.659 6.203l4.567 2.284A3 3 0 0 1 22 14.236V15a2.235 2.235 0 0 1-3.236 2L4.843 10.04a3 3 0 0 1-.78-.562l-.98-.98a2.55 2.55 0 0 1-.477-2.945L2.882 5c.306-.613.933-1 1.618-1h.028c.466-.001.925.107 1.342.317Z");
}

.dubabk8wl {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m7 6l2 1l1.776-3.553A.81.81 0 0 1 11.5 3c.303 0 .577.18.697.46L15 10l4.894 2.447A2 2 0 0 1 21 14.237V15c0 .919-.967 1.517-1.789 1.106l-13.92-6.96a2 2 0 0 1-.52-.376l-.98-.98A1.55 1.55 0 0 1 3.5 6l.276-.553A.81.81 0 0 1 4.5 5h.028a2 2 0 0 1 .894.211zM3 21h18");
}

.ft5dv1b6b {
  fill: none;
}

</style>
