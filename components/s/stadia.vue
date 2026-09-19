<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j93d6ebrd"/><path class="ogla-z0tt"/><path class="mepfddbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:stadia" /></template>
<style>
.j93d6ebrd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 19.323a33.5 33.5 0 0 1 39-3.298");
}

.mepfddbyr {
  fill: none;
  stroke: currentColor;
  d: path("m4.5 19.323l3.875 9.48M43.5 16.025l-2.343 5.8m-3.384 3.907l-1.813 6.066M14.476 30.76l2.626 5.972");
}

.ogla-z0tt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.157 21.825a33.3 33.3 0 0 0-28.269-.636a33.5 33.5 0 0 1 6.775-.779a33.33 33.33 0 0 1 18.093 5.305m-23.28 5.045c4.431-2.508 8.19-3.988 13.603-4.243a33.6 33.6 0 0 0-6.982-.735a27.7 27.7 0 0 0-12.723 3.02m8.729 7.931a33.33 33.33 0 0 1 17.547-4.961q.634 0 1.262.023");
}

</style>
