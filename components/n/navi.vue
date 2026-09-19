<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xr8jjlbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:navi" /></template>
<style>
.xr8jjlbvg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.386 5.5v20.44h-8.222V13.724H21.953V5.5zm-28.55 12.328H5.614V42.5h8.222V26.05m.044-8.223h4.674c2.897 0 3.203-.345 7.658 4.111c4.456 4.457 4.111 4.58 4.111 7.402V42.5h-3.906c-1.227 0-2.716-.179-3.53-1.038c-.814-.858-.787-2.187-.787-3.326V26.05h-8.22");
}

</style>
