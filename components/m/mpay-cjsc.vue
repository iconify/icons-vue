<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sw7l_8bji"/><path class="rkwzy1h3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mpay-cjsc" /></template>
<style>
.rkwzy1h3k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.018 20.324L24 13.319L7.982 20.324m30.138 9.843L24 23.992L9.88 30.167m22.101 8L24 34.683l-7.981 3.484");
}

.sw7l_8bji {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.5c13.123-7.969 16.3-10.957 16.3-31.874L24 4.5L7.7 11.626C7.7 32.543 10.877 35.53 24 43.5");
}

</style>
