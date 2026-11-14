<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uy1im_bxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:star-bright" /></template>
<style>
.uy1im_bxx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.75 8l.407 1.087a1.5 1.5 0 0 0 1.317.97l1.229.073a.765.765 0 0 1 .422 1.37l-.846.651a1.5 1.5 0 0 0-.541 1.552L15 14.75a.817.817 0 0 1-1.234.885l-.955-.614a1.5 1.5 0 0 0-1.622 0l-.955.614A.817.817 0 0 1 9 14.75l.262-1.047a1.5 1.5 0 0 0-.541-1.552l-.846-.651a.765.765 0 0 1 .422-1.37l1.229-.073a1.5 1.5 0 0 0 1.317-.97L11.25 8a.801.801 0 0 1 1.5 0m4-2.5l1-1.5m1.75 10.5l2 .5M12 20v2m-7.5-7.5l-2 .5m4.75-9.5l-1-1.5");
}

</style>
