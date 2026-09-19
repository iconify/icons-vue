<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pfn5t1bmr"/><path class="g8d26m50m"/><g class="y9tr6bcfx"><path class="walxuubko"/><path class="qu2m0qbjz"/></g><ellipse class="uciru1ieh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:phoenix" /></template>
<style>
.g8d26m50m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.879 6.713c5.886-3.357 13.458-2.857 18.76 1.24c5.302 4.095 7.13 10.857 4.528 16.752c-2.601 5.896-9.04 9.585-15.954 9.142S10.482 28.928 8.799 22.758");
}

.pfn5t1bmr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.802 43.498h3.488c1.842 0 5.786-2.748 5.786-5.493v-5.17");
}

.qu2m0qbjz {
  d: path("M18.498 19.49v-7.149c0-2.4-1.594-4.53-2.762-5.571");
}

.uciru1ieh {
  cx: 24.447px;
  cy: 19.104px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.959px;
  ry: 5.872px;
}

.walxuubko {
  d: path("M15.738 6.779S13.133 4.974 10.63 4.86c-.298-.014-1.963-.144-2.97-.103M8.797 43.5V8.127s-.065-2.762-1.13-3.361");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
