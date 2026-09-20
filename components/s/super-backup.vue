<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="mkpgasb1s"/><path class="w2fd06oeo"/><circle class="swx-mebbo"/><circle class="cp57egb3t"/><path class="a9ry_rb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:super-backup" /></template>
<style>
.a9ry_rb_y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 24.649c5.41 0 9.384-3.894 8.923-8.269c-.419-3.965-4.398-6.916-8.923-6.916s-8.504 2.951-8.923 6.916c-.267 2.531 2.219 4.072 2.219 4.072l1.954-4.072h-4.173");
}

.cp57egb3t {
  cx: 40.913px;
  cy: 39.513px;
  r: 0.75px;
  fill: currentColor;
}

.mkpgasb1s {
  width: 39px;
  height: 5.983px;
  x: 4.5px;
  y: 36.522px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.991px;
}

.swx-mebbo {
  cx: 7.087px;
  cy: 39.513px;
  r: 0.75px;
  fill: currentColor;
}

.w2fd06oeo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.085 30.81za2.774 2.774 0 0 0-2.775-2.774H8.69a2.774 2.774 0 0 0-2.775 2.774M38.326 7.693za2.2 2.2 0 0 0-2.198-2.198H11.872a2.2 2.2 0 0 0-2.198 2.198m0 0L4.5 39.513m33.826-31.82L43.5 39.514m-24.942-.001h10.884");
}

</style>
