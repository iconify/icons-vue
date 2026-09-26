<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kibqgsb0e"/><path class="swuddpb2r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:volume-off-fill" /></template>
<style>
.kibqgsb0e {
  fill: currentColor;
  d: path("M12 12L12 18.9962C12 20.9544 9.4772 21.746 8.3585 20.1388L5.4777 16L3 16C1.8954 16 1 15.1046 1 14L1 10C1 8.8954 1.8954 8 3 8L5.4777 8L6.5128 6.5128Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.swuddpb2r {
  d: path("M15.8044 6.9091C17.2058 8.2316 18 10.0732 18 12C18 12.112 17.9973 12.2238 17.992 12.3351M18.5498 4C20.7519 6.0782 22 8.9721 22 12C22 13.2746 21.7788 14.5254 21.3585 15.7016M2 2L22 22");
}

</style>
