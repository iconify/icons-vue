<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkdox_x_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:trash-x-sharp" /></template>
<style>
.pkdox_x_z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.75 6.25l.85 12.2l.182 1.809L8.6 20.25h6.8l1.818.009l.182-1.809l.85-12.2Zm-2 0h16.5M9 6.25v-3h6v3m-4.75 4.5v5m3.5-5v5");
}

</style>
