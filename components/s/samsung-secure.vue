<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vpg773bsx"/><path class="unqq8hx3g"/><path class="x41yijb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:samsung-secure" /></template>
<style>
.unqq8hx3g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.246 26.606l4.135 4.135l5.373-5.372m-8.934-9.282a4.087 4.087 0 1 1 8.174 0m0 0v4.023m-8.172-4.108v4.108");
}

.vpg773bsx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.134 36V20.11h19.732M19.279 36h14.587V25.45");
}

.x41yijb3r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.288 44.566a21.516 21.516 0 1 1 9.69-6.18");
}

</style>
