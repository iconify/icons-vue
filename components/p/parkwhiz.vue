<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uj375ccgj"/><path class="ua9z7g1kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:parkwhiz" /></template>
<style>
.ua9z7g1kr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.5 34.5a2 2 0 1 0 2 2V20c0-8.008 6.492-14.5 14.5-14.5S42.5 11.992 42.5 20S36.008 34.5 28 34.5H17.5");
}

.uj375ccgj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.5 30.5a6 6 0 1 0 6 6V20c0-5.799 4.701-10.5 10.5-10.5S38.5 14.201 38.5 20S33.799 30.5 28 30.5H17.5");
}

</style>
