<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvwt0-_na"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:nerve" /></template>
<style>
.hvwt0-_na {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10.5c4 0 5.5-1.5 8-2.5S14 4.5 17 4c2-.25 3.5-1 4.5-1.5M2.5 12C6 12 8 13 11 12s5.5.5 10.5 0m-19 1.5c4 0 5.5 1.5 8 2.5s3.5 3.5 6.5 4c2 .25 3.5 1 4.5 1.5");
}

</style>
