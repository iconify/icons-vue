<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m-_30vdcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tvtime" /></template>
<style>
.m-_30vdcl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5h12.333v12.333H5.5zm12.334 0h12.333v12.333H17.834zm12.333 0H42.5v12.333H30.167zM17.834 17.834h12.333v12.333H17.834zm0 12.333h12.333V42.5H17.834z");
}

</style>
