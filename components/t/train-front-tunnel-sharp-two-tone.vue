<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="tzxz_cc4s"/><path class="kydl28zol"/><path clip-rule="evenodd" class="bjulqo_nq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:train-front-tunnel-sharp-two-tone" /></template>
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

.tzxz_cc4s {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 6H18C18.552 6 19 6.448 19 7V19C19 19.552 18.552 20 18 20H6C5.448 20 5 19.552 5 19V7C5 6.448 5.448 6 6 6H12Z");
  stroke: none;
}

</style>
