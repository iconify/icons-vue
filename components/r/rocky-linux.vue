<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a6_avtc6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rocky-linux" /></template>
<style>
.a6_avtc6n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.304 31.1A21.5 21.5 0 0 0 45.5 24c0-11.87-9.63-21.5-21.5-21.5S2.5 12.13 2.5 24a21.37 21.37 0 0 0 6.181 15.072l21.814-21.814l13.818 13.818zm-3.92 6.83l-9.898-9.899L14.988 43.53a21.35 21.35 0 0 0 9.002 1.97c6.562 0 12.43-2.934 16.371-7.57z");
}

</style>
