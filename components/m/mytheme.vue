<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nmyupdz9y"/><path class="xa8seibsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mytheme" /></template>
<style>
.nmyupdz9y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.25 24A9.25 9.25 0 1 0 24 14.75v18.5A9.25 9.25 0 1 1 14.75 24z");
}

.xa8seibsi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.75 24A9.25 9.25 0 1 1 24 14.75v18.5A9.25 9.25 0 1 0 33.25 24z");
}

</style>
