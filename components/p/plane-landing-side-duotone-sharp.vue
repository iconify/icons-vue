<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gzcplbckv"/><path class="szfgbd29s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-landing-side-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gzcplbckv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8.553 5.658L9.882 3a1.794 1.794 0 0 1 2.586-.71c.289.188.514.458.648.776l2.659 6.203l5.119 2.56A2 2 0 0 1 22 13.618v1.764a2 2 0 0 1-2.894 1.789L4.698 9.967a2 2 0 0 1-.52-.375L2.803 8.217a2 2 0 0 1-.375-2.309L2.882 5c.306-.613.933-1 1.618-1h.264c.311-.001.617.071.894.211Z");
}

.szfgbd29s {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m7 6l2 1l1.776-3.553A.81.81 0 0 1 11.5 3c.303 0 .577.18.697.46L15 10l5.447 2.724a1 1 0 0 1 .553.894v1.764a1 1 0 0 1-1.447.894L5.145 9.073a1 1 0 0 1-.26-.188L3.51 7.51a1 1 0 0 1-.188-1.155l.454-.908A.81.81 0 0 1 4.5 5h.264a1 1 0 0 1 .447.106zM3 21h18");
}

</style>
