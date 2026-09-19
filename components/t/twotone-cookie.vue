<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_g0lacvd"/><circle class="pmqt2cblr"/><circle class="x-l7iicwp"/><circle class="j773sojgf"/><path class="qvnlgot3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-cookie" /></template>
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

.qvnlgot3c {
  fill: currentColor;
  d: path("M21.95 10.99c-1.79-.03-3.7-1.95-2.68-4.22c-2.97 1-5.78-1.59-5.19-4.56C7.1.74 2 6.41 2 12c0 5.52 4.48 10 10 10c5.89 0 10.54-5.08 9.95-11.01M12 20c-4.41 0-8-3.59-8-8c0-3.31 2.73-8.18 8.08-8.02c.42 2.54 2.44 4.56 4.99 4.94c.07.36.52 2.55 2.92 3.63C19.7 16.86 16.06 20 12 20");
}

.t_g0lacvd {
  fill: currentColor;
  d: path("M17.07 8.93c-2.55-.39-4.57-2.41-4.99-4.94C6.73 3.82 4 8.69 4 12c0 4.41 3.59 8 8 8c4.06 0 7.7-3.14 7.98-7.45a5.03 5.03 0 0 1-2.91-3.62M8.5 15c-.83 0-1.5-.67-1.5-1.5S7.67 12 8.5 12s1.5.67 1.5 1.5S9.33 15 8.5 15m2-5C9.67 10 9 9.33 9 8.5S9.67 7 10.5 7s1.5.67 1.5 1.5s-.67 1.5-1.5 1.5m4.5 6c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.x-l7iicwp {
  cx: 8.5px;
  cy: 13.5px;
  r: 1.5px;
  fill: currentColor;
}

</style>
