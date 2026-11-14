<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iq6k1z49a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:projector-screen" /></template>
<style>
.iq6k1z49a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5h19M4 3.5V15a1.5 1.5 0 0 0 1.5 1.5h13A1.5 1.5 0 0 0 20 15V3.5m-8 13v4");
}

</style>
