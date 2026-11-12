<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="niw2nebei"/><path class="evr7kjbjs"/><path class="a2-o1jt_u"/><path class="d6cn3zbnj"/><path class="fmc_3temv"/><path class="avgpambcj"/><path class="ko6o-6b9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:safe-circle-broken" /></template>
<style>
.a2-o1jt_u {
  d: path("M16 10L17 9");
}

.avgpambcj {
  d: path("M17 15L16 14");
}

.d6cn3zbnj {
  d: path("M11 15L12 14");
}

.evr7kjbjs {
  d: path("M14 14C12.8954 14 12 13.1046 12 12C12 10.8954 12.8954 10 14 10C15.1046 10 16 10.8954 16 12C16 13.1046 15.1046 14 14 14Z");
}

.fmc_3temv {
  d: path("M12 10L11 9");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ko6o-6b9b {
  d: path("M7 3.33782C8.47087 2.48697 10.1786 2 12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 10.1786 2.48697 8.47087 3.33782 7");
}

.niw2nebei {
  d: path("M7 8L7 9M7 12L7 16");
}

</style>
