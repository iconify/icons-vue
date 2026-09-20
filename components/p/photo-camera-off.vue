<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="yf5990mft"/><path clip-rule="evenodd" class="wx-1x701q"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:photo-camera-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.wx-1x701q {
  fill-rule: evenodd;
  d: path("M6.5 11.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 0 0-7 0m5 0a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0");
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

.yf5990mft {
  fill-rule: evenodd;
  d: path("M5.696 5.078L5.398 6H4.5a3 3 0 0 0-3 3v6a3 3 0 0 0 3 3h11a3 3 0 0 0 3-3V9a3 3 0 0 0-3-3h-.899l-.297-.922A3 3 0 0 0 11.449 3H8.55a3 3 0 0 0-2.855 2.078M4.5 8h2.354L7.6 5.693A1 1 0 0 1 8.551 5h2.898a1 1 0 0 1 .951.693L13.145 8H15.5a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-11a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1");
}

</style>
