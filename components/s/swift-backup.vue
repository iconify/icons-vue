<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yf0sgtiyb"/><path class="j4s1ueoeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:swift-backup" /></template>
<style>
.j4s1ueoeq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.444 25.179v7.481L24 42.5m16.444-37v7.481L30.251 19.08M7.556 5.5h32.888");
}

.yf0sgtiyb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.444 25.179L7.556 5.5m27.792 30.21L7.556 19.08v13.58L24 42.5");
}

</style>
