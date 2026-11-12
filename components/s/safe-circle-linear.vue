<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="w3r9-bcte"/><path class="xng-4w08c"/><path class="evr7kjbjs"/><path class="a2-o1jt_u"/><path class="d6cn3zbnj"/><path class="fmc_3temv"/><path class="avgpambcj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:safe-circle-linear" /></template>
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

.w3r9-bcte {
  d: path("M12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22Z");
}

.xng-4w08c {
  d: path("M7 8L7 16");
}

</style>
