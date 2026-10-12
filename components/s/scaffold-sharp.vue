<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxg23cj0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:scaffold-sharp" /></template>
<style>
.rxg23cj0k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 2.75v18.5M12 2.75v18.5m7.5-18.5v18.5M2.75 8.5h18.5M2.75 15h18.5M4.5 8.5L12 15m0 0l7.5 6.25M12 2.75l7.5 5.75");
}

</style>
