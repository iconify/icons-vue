<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdo5mv6fs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pallet-sharp" /></template>
<style>
.rdo5mv6fs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 3.25h13.5v6.5H5.25zm6.75 0v2.5M2.75 12h18.5v2.5H2.75zm2.75 2.5v3.75M12 14.5v3.75m6.5-3.75v3.75m-15.75.25h18.5v2.75H2.75z");
}

</style>
