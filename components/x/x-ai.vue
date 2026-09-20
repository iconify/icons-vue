<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":196};
const content = `<path class="mux7nclcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:x-ai" /></template>
<style>
.mux7nclcm {
  d: path("M512 .18c-59.067 4.815-291.259 33.6-452.256 195.45H0l6.675-6.653C40.367 156.428 189.448 18.481 512 0zM155.917 138.078l79.048 57.553h-46.807l-14.198-10.328H94.687a550 550 0 0 1 16.94-14.436h42.463l-21.974-15.984a589 589 0 0 1 23.8-16.805m40.437-24.897L309.8 195.63h-46.828l-92.261-67.16a635 635 0 0 1 25.642-15.29M17.839 71.77l46.764.022l36.094 26.23A645 645 0 0 0 75.46 113.67z");
}

</style>
