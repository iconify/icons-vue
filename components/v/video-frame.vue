<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="fr9wc8ere"/><rect class="l7qlfssbq"/><path class="mt_lawbsd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:video-frame" /></template>
<style>
.fr9wc8ere {
  width: 18.5px;
  height: 16.5px;
  x: 2.75px;
  y: 3.75px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l7qlfssbq {
  width: 12.5px;
  height: 10.5px;
  x: 5.75px;
  y: 6.75px;
  rx: 1.5px;
}

.mt_lawbsd {
  d: path("m8.5 14.25l2.75-2.75l2 2l1.25-1.25l1.5 1.5");
}

</style>
