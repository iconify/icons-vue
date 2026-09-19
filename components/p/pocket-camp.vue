<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t1dnxj7yq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pocket-camp" /></template>
<style>
.t1dnxj7yq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.9 12.455c1.08-1.606 6.77-2.043 9.948-3.53c-3.043-1.22-8.255-2.387-10.053-3.425zM24.459 33.4l-5.592 8.739l-11.773-.555l17.754-27.641L40.906 42.5l-11.653-.365z");
}

</style>
