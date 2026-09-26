<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="u-th1gbxa"/><path class="o4kr9t73l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:toggle-on-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o4kr9t73l {
  d: path("M14.5 10L17.5 10C17.7761 10 18 10.2239 18 10.5L18 13.5C18 13.7761 17.7761 14 17.5 14L14.5 14C14.2239 14 14 13.7761 14 13.5L14 10.5C14 10.2239 14.2239 10 14.5 10Z");
}

.u-th1gbxa {
  d: path("M2.5 6L21.5 6C21.7761 6 22 6.2239 22 6.5L22 17.5C22 17.7761 21.7761 18 21.5 18L2.5 18C2.2239 18 2 17.7761 2 17.5L2 6.5C2 6.2239 2.2239 6 2.5 6Z");
}

</style>
