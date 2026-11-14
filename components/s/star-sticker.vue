<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="skio7kbow"/><path class="ktpg_ebwv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:star-sticker" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ktpg_ebwv {
  d: path("M19 17c-2.5 0-5 2-5.5 4.5");
}

.skio7kbow {
  d: path("m13.323 6.055l.971 2.06a1.5 1.5 0 0 0 1.168.848l2.259.288a1.462 1.462 0 0 1 .818 2.515l-1.66 1.561a1.5 1.5 0 0 0-.446 1.372l.425 2.238a1.462 1.462 0 0 1-2.139 1.555l-1.997-1.096a1.5 1.5 0 0 0-1.444 0l-1.997 1.096a1.462 1.462 0 0 1-2.139-1.555l.425-2.238a1.5 1.5 0 0 0-.446-1.372l-1.66-1.561a1.462 1.462 0 0 1 .818-2.515l2.259-.288a1.5 1.5 0 0 0 1.168-.848l.971-2.06a1.462 1.462 0 0 1 2.646 0");
}

</style>
