<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_s39c2mu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:outdent-sharp" /></template>
<style>
.t_s39c2mu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 4.5h16.5m-9 5h9m-9 5h9m-16.5 5h16.5M8.75 12h-5m2.5-2.5L3.75 12l2.5 2.5");
}

</style>
