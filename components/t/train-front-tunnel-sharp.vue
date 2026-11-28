<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kydl28zol"/><path clip-rule="evenodd" class="bjulqo_nq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:train-front-tunnel-sharp" /></template>
<style>
.bjulqo_nq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 15C11 15.552 10.552 16 10 16C9.448 16 9 15.552 9 15C9 14.448 9.448 14 10 14C10.552 14 11 14.448 11 15ZM15 15C15 15.552 14.552 16 14 16C13.448 16 13 15.552 13 15C13 14.448 13.448 14 14 14C14.552 14 15 14.448 15 15Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kydl28zol {
  d: path("M2 23V2H22V23M6 11H18M8 19L6.224 22.553M16 19L17.776 22.553M6 7H18V19H6V7Z");
}

</style>
