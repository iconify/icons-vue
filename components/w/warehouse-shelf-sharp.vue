<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yk-_l1miw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:warehouse-shelf-sharp" /></template>
<style>
.yk-_l1miw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 2.75v18.5m17-18.5v18.5M3.5 5.5h17M3.5 13h17m-17 7.5h17M8 8.5h7.5V13H8zm3.75 0v2");
}

</style>
