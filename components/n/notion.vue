<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ta0mo1bsh"/><path class="mvp9rjb1q"/><path class="ng05lab9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:notion" /></template>
<style>
.mvp9rjb1q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.141 12.098L32.215 5.5L6.269 7.296l5.645 6.268");
}

.ng05lab9w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.643 42.5l-5.784-8.137l.41-27.067m14.792 29.402V19.954l12.546 16.385V19.057M18.745 36.855l4.633-.314m-4.633-16.587h2.316m10.23-.74l4.632-.315");
}

.ta0mo1bsh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.141 41.537l-30.498.963l.271-28.936l30.227-1.466z");
}

</style>
