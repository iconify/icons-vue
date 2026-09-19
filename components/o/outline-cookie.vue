<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="pmqt2cblr"/><circle class="x-l7iicwp"/><circle class="j773sojgf"/><path class="roexocb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-cookie" /></template>
<style>
.j773sojgf {
  cx: 15px;
  cy: 15px;
  r: 1px;
  fill: currentColor;
}

.pmqt2cblr {
  cx: 10.5px;
  cy: 8.5px;
  r: 1.5px;
  fill: currentColor;
}

.roexocb7o {
  fill: currentColor;
  d: path("M21.95 10.99c-1.79-.03-3.7-1.95-2.68-4.22c-2.97 1-5.78-1.59-5.19-4.56C7.11.74 2 6.41 2 12c0 5.52 4.48 10 10 10c5.89 0 10.54-5.08 9.95-11.01M12 20c-4.41 0-8-3.59-8-8c0-3.31 2.73-8.18 8.08-8.02c.42 2.54 2.44 4.56 4.99 4.94c.07.36.52 2.55 2.92 3.63C19.7 16.86 16.06 20 12 20");
}

.x-l7iicwp {
  cx: 8.5px;
  cy: 13.5px;
  r: 1.5px;
  fill: currentColor;
}

</style>
