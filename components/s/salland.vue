<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zt2bgsrtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:salland" /></template>
<style>
.zt2bgsrtm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.22 10.319c9.891-7.86 18.28-1.413 18.28 7.329c0 7.947-14.217 18.986-20.575 23.578m-4.15-5.564C7.794 26.302 5.5 24.36 5.5 18.354s8.124-11.215 13.687-3.09");
}

</style>
