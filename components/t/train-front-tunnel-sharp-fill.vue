<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="bo-14k95d"/><path class="wdapgsben"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:train-front-tunnel-sharp-fill" /></template>
<style>
.bo-14k95d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 6L18 6C18.5523 6 19 6.4477 19 7L19 19C19 19.5523 18.5523 20 18 20L6 20C5.4477 20 5 19.5523 5 19L5 7C5 6.4477 5.4477 6 6 6ZM12 8L7 8L7 10L17 10L17 8ZM11 15C11 14.4477 10.5523 14 10 14C9.4477 14 9 14.4477 9 15C9 15.5523 9.4477 16 10 16C10.5523 16 11 15.5523 11 15ZM15 15C15 14.4477 14.5523 14 14 14C13.4477 14 13 14.4477 13 15C13 15.5523 13.4477 16 14 16C14.5523 16 15 15.5523 15 15Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wdapgsben {
  d: path("M2 23L2 2L22 2L22 23M8 19L6.2236 22.5528M16 19L17.7764 22.5528");
}

</style>
