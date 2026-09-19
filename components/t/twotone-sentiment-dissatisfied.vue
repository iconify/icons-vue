<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yws7ocbdf"/><circle class="mmn7xsb7v"/><circle class="an0_1xo_x"/><path class="y1wqt1_ee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-sentiment-dissatisfied" /></template>
<style>
.an0_1xo_x {
  cx: 8.5px;
  cy: 9.5px;
  r: 1.5px;
  fill: currentColor;
}

.mmn7xsb7v {
  cx: 15.5px;
  cy: 9.5px;
  r: 1.5px;
  fill: currentColor;
}

.y1wqt1_ee {
  fill: currentColor;
  d: path("M11.99 2C6.47 2 2 6.48 2 12s4.47 10 9.99 10C17.52 22 22 17.52 22 12S17.52 2 11.99 2M12 20c-4.42 0-8-3.58-8-8s3.58-8 8-8s8 3.58 8 8s-3.58 8-8 8m0-6c-2.33 0-4.32 1.45-5.12 3.5h1.67c.69-1.19 1.97-2 3.45-2s2.75.81 3.45 2h1.67c-.8-2.05-2.79-3.5-5.12-3.5");
}

.yws7ocbdf {
  fill: currentColor;
  d: path("M12 4c-4.42 0-8 3.58-8 8s3.58 8 8 8s8-3.58 8-8s-3.58-8-8-8m3.5 4c.83 0 1.5.67 1.5 1.5s-.67 1.5-1.5 1.5s-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5m-7 0c.83 0 1.5.67 1.5 1.5S9.33 11 8.5 11S7 10.33 7 9.5S7.67 8 8.5 8m6.95 9.5c-.7-1.19-1.97-2-3.45-2s-2.76.81-3.45 2H6.88a5.495 5.495 0 0 1 10.24 0z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
