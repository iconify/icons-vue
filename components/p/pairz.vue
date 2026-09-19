<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="c8ufofb0o"/><rect class="mk9je8b8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pairz" /></template>
<style>
.c8ufofb0o {
  width: 17.608px;
  height: 17.608px;
  x: 4.5px;
  y: 15.196px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.mk9je8b8g {
  width: 17.608px;
  height: 17.608px;
  x: 25.892px;
  y: 15.196px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
