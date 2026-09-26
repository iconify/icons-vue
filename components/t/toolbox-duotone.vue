<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w72bo_4bl"/><path class="igf8p5ula"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:toolbox-duotone" /></template>
<style>
.igf8p5ula {
  d: path("M4 14L20 14M8 12L8 16M16 12L16 16M8 8L8 5C8 3.8954 8.8954 3 10 3L14 3C15.1046 3 16 3.8954 16 5L16 8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w72bo_4bl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.7071 7.8787C4.2697 7.3161 5.0328 7 5.8284 7L18.1716 7C18.9672 7 19.7303 7.3161 20.2929 7.8787L22.1213 9.7071C22.6839 10.2697 23 11.0328 23 11.8284L23 18C23 20.2091 21.2091 22 19 22L5 22C2.7909 22 1 20.2091 1 18L1 11.8284C1 11.0328 1.3161 10.2697 1.8787 9.7071L3.7071 7.8787Z");
  stroke: none;
}

</style>
