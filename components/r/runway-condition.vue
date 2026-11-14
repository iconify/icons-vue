<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lz0m_zzqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:runway-condition" /></template>
<style>
.lz0m_zzqh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.616 21.5H3.5L8 2.5h4.5l2.328 11.058M10.25 6v3M10 12.5v3m8.5 0v6M16 17l5 3m-5 0l5-3");
}

</style>
