<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vkhdwpbny"/><path class="k--td0b5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ou-study" /></template>
<style>
.k--td0b5u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.93 8.535a5.76 5.76 0 0 1 5.764 5.765a5.766 5.766 0 0 1-5.765 5.765c-3.176 0-5.752-2.588-5.752-5.765a5.757 5.757 0 0 1 5.752-5.765");
}

.vkhdwpbny {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.447 27.947V5.5h29.106v22.447C38.553 35.985 32.037 42.5 24 42.5S9.447 35.984 9.447 27.947");
}

</style>
