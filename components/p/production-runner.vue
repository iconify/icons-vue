<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4xxn71zs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:production-runner" /></template>
<style>
.t4xxn71zs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.2 21.5H4V7h11.5v6.9M7 7V2.5m.5 10H12m3 4.75h6.5v4.25H15Zm0 0l5.75-2.75");
}

</style>
