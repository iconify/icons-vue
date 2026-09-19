<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k-su3tqtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:summit" /></template>
<style>
.k-su3tqtj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.394 14.32L24 18.124l3.606-3.803zM24 38.052L4.5 33.367L24 9.949zl19.5-4.685L24 9.949");
}

</style>
