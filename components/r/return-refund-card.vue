<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fyhcivbxa"/><path class="txdf6pbob"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:return-refund-card" /></template>
<style>
.fyhcivbxa {
  d: path("M12.1 19H2.5V5h19v10.2m-19-5.7h19m-19 0h19M6 15h2.5M21 18h-6");
}

.txdf6pbob {
  d: path("M17.5 15.5L15 18l2.5 2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
