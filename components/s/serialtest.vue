<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rw2yjhb1h"/><path class="tyu51720p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:serialtest" /></template>
<style>
.rw2yjhb1h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.035 24.943l-3.067 3.04c-7.262 8.145 4.637 19.731 12.742 11.936l7.018-7.42c2.864-3.825 2.39-8.392-1.525-12.227l-2.29-2.353");
}

.tyu51720p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.848 23.922l3.543-3.404c6.122-6.74-3.862-19.95-11.72-13.104l-8.42 8.61c-2.526 2.984-2.467 7.898 2.084 12.016l2.147 2.295");
}

</style>
