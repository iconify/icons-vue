<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(-30 22.885 32.496)" class="kj8awyb6i"/><rect transform="rotate(-30 25.115 15.504)" class="p8bgisb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:supercards" /></template>
<style>
.kj8awyb6i {
  width: 23.674px;
  height: 13.601px;
  x: 11.048px;
  y: 25.696px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.198px;
  ry: 2.198px;
}

.p8bgisb3l {
  width: 23.674px;
  height: 13.601px;
  x: 13.277px;
  y: 8.703px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.198px;
  ry: 2.198px;
}

</style>
