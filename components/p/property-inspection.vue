<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trgtsnbjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:property-inspection" /></template>
<style>
.trgtsnbjj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.561 3.561L9.25 6.25a1.5 1.5 0 0 0 .586.362L11 7a.977.977 0 0 1 .382 1.618l-2.764 2.764A.977.977 0 0 1 7 11l-.388-1.164a1.5 1.5 0 0 0-.362-.586L3.561 6.561a1.5 1.5 0 0 1 0-2.122l.878-.878a1.5 1.5 0 0 1 2.122 0m7.84 13.507l1.75-1.884a1.5 1.5 0 0 1 2.198 0l1.75 1.884a1.5 1.5 0 0 1 .401 1.021V20a1.5 1.5 0 0 1-1.5 1.5h-3.5A1.5 1.5 0 0 1 14 20v-1.911a1.5 1.5 0 0 1 .401-1.021M13.75 8.5l7.75 4m-13 1.25l3 7.75");
}

</style>
