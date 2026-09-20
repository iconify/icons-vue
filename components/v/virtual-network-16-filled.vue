<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a0av1miwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:virtual-network-16-filled" /></template>
<style>
.a0av1miwu {
  fill: currentColor;
  d: path("M2.92 4.776a.75.75 0 1 1 1.16.949L2.22 7.999l1.862 2.278a.75.75 0 0 1-1.162.95L.67 8.475a.75.75 0 0 1 .001-.95zm9.106-.106a.75.75 0 0 1 1.054.106l2.25 2.75a.75.75 0 0 1 .001.949l-2.25 2.752a.75.75 0 0 1-1.162-.95l1.862-2.278l-1.86-2.274a.75.75 0 0 1 .105-1.055m-.9 2.46a.875.875 0 1 1-.001 1.75a.875.875 0 0 1 0-1.75m-6.25-.005a.875.875 0 1 1-.001 1.75a.875.875 0 0 1 0-1.75m3.124 0a.875.875 0 1 1 0 1.75a.875.875 0 0 1 0-1.75");
}

</style>
