<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="o607hcbco"/><path class="bjd7f00ll"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-off-duotone-round" /></template>
<style>
.bjd7f00ll {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m7.658 10.658l-1.413 1.777A.965.965 0 0 0 7 14h1.25a2 2 0 0 1 2 2v3c0 .661.833.952 1.245.435l2.189-2.751m2.658-3.342l1.413-1.777A.965.965 0 0 0 17 10h-1.25a2 2 0 0 1-2-2V5c0-.661-.833-.952-1.245-.435l-2.189 2.751M2 5l17 17");
}

.ft5dv1b6b {
  fill: none;
}

.o607hcbco {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m16.342 13.342l-6.026-6.026l2.189-2.751A.7.7 0 0 1 13.75 5v3a2 2 0 0 0 2 2H17a.966.966 0 0 1 .755 1.565Zm-4.847 6.093A.7.7 0 0 1 10.25 19v-3a2 2 0 0 0-2-2H7a.966.966 0 0 1-.755-1.565l1.413-1.777l6.026 6.026Z");
}

</style>
