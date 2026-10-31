<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ac-ri_bdo"/><path class="jf-uovv_h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:washing-machine-sharp" /></template>
<style>
.ac-ri_bdo {
  d: path("M4 2L20 2L20 22L4 22ZM16 14C16 16.2091 14.2091 18 12 18C9.7909 18 8 16.2091 8 14C8 11.7909 9.7909 10 12 10C14.2091 10 16 11.7909 16 14ZM11 6L17 6");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jf-uovv_h {
  fill: currentColor;
  d: path("M9 6C9 6.5523 8.5523 7 8 7C7.4477 7 7 6.5523 7 6C7 5.4477 7.4477 5 8 5C8.5523 5 9 5.4477 9 6Z");
  stroke: none;
}

</style>
