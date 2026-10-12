<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p63g7ukwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:soap-dispenser-sharp" /></template>
<style>
.p63g7ukwk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 7.75v-3m3 0H7.25v2m2.75 1h4v2.5h-4zm-3.75 2.5h11.5v11H6.25zm3 4.5h5.5");
}

</style>
