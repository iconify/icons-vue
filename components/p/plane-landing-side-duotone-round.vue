<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zofldydkl"/><path class="dubabk8wl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-landing-side-duotone-round" /></template>
<style>
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

.zofldydkl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m7 6l2 1l1.776-3.553c.292-.582 1.156-.605 1.421.013L15 10l4.894 2.447A2 2 0 0 1 21 14.236V15a1.236 1.236 0 0 1-1.789 1.106L5.29 9.145a2 2 0 0 1-.519-.374l-.98-.98A1.55 1.55 0 0 1 3.5 6l.276-.553A.81.81 0 0 1 4.5 5h.028c.31 0 .617.072.894.211Z");
}

</style>
