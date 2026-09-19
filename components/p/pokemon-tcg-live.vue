<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="vx3_zx4kd"/><circle class="xxqd7jynt"/><path class="qzfc6-0-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pokemon-tcg-live" /></template>
<style>
.qzfc6-0-u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.064 23.99h6.002m7.848 0h6.002M9.553 4.5h28.894v39H9.553z");
}

.vx3_zx4kd {
  cx: 23.99px;
  cy: 23.99px;
  r: 9.926px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xxqd7jynt {
  cx: 23.99px;
  cy: 23.99px;
  r: 3.924px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
