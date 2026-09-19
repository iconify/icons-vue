<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n2cjm_-vy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:trackgraph" /></template>
<style>
.n2cjm_-vy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 20.22H27.78V5.5h-7.56v14.72H5.5v7.56h14.72V42.5h7.56V27.78H42.5z");
}

</style>
