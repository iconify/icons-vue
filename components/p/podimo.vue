<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bvb25_-ve"/><circle class="t-le7-bla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:podimo" /></template>
<style>
.bvb25_-ve {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.946 35.744V6.038c0-.85.689-1.538 1.538-1.538c8.597 0 15.566 6.969 15.566 15.566v1.65c0 8.597-6.97 15.566-15.566 15.566c-.85 0-1.538-.688-1.538-1.538M7.95 27.217V5.618c0-.617.501-1.118 1.119-1.118c6.25 0 11.317 5.067 11.317 11.317v1.201c0 6.25-5.067 11.317-11.317 11.317c-.618 0-1.119-.5-1.119-1.118");
}

.t-le7-bla {
  cx: 14.168px;
  cy: 37.282px;
  r: 6.218px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
