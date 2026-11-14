<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tn1mo4_gg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ski-poles-crossed" /></template>
<style>
.tn1mo4_gg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 20.5l11-14m2 14l-11-14m11.385-3.523za1.5 1.5 0 0 1 .259 2.105l-.924 1.183a1.5 1.5 0 0 1-2.105.258a1.5 1.5 0 0 1-.259-2.105l.924-1.183a1.5 1.5 0 0 1 2.105-.258m-13.77 0za1.5 1.5 0 0 1 2.105.258l.924 1.183a1.5 1.5 0 0 1-.259 2.105a1.5 1.5 0 0 1-2.105-.258l-.924-1.183a1.5 1.5 0 0 1 .259-2.105M5.5 17.25l3 2.5m10-2.5l-3 2.5");
}

</style>
