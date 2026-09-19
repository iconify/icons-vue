<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bk0-bf-rc"/><path class="xt0y75bun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mycricket" /></template>
<style>
.bk0-bf-rc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.86 33.81l7.84 8.4h11.66l-13.61-14.3");
}

.xt0y75bun {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.71 43l-.06-11.67l17-16.71H38Zm-.07-11.67L9.82 5h8.12v18.16");
}

</style>
