<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mq58-1b6e"/><path class="a47ljxbek"/><circle class="uyhfztemm"/><circle class="een6afftk"/><circle class="ac2-8hbbw"/><path class="yp7tiudbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-sports-golf" /></template>
<style>
.a47ljxbek {
  fill: currentColor;
  d: path("M12 16c3.87 0 7-3.13 7-7s-3.13-7-7-7s-7 3.13-7 7s3.13 7 7 7m0-12c2.76 0 5 2.24 5 5s-2.24 5-5 5s-5-2.24-5-5s2.24-5 5-5");
}

.ac2-8hbbw {
  cx: 12px;
  cy: 6px;
  r: 1px;
  fill: currentColor;
}

.een6afftk {
  cx: 14px;
  cy: 8px;
  r: 1px;
  fill: currentColor;
}

.mq58-1b6e {
  fill: currentColor;
  d: path("M12 14c2.76 0 5-2.24 5-5s-2.24-5-5-5s-5 2.24-5 5s2.24 5 5 5m2-7c.55 0 1 .45 1 1s-.45 1-1 1s-1-.45-1-1s.45-1 1-1m-2-2c.55 0 1 .45 1 1s-.45 1-1 1s-1-.45-1-1s.45-1 1-1m-2 2c.55 0 1 .45 1 1s-.45 1-1 1s-1-.45-1-1s.45-1 1-1");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.uyhfztemm {
  cx: 10px;
  cy: 8px;
  r: 1px;
  fill: currentColor;
}

.yp7tiudbf {
  fill: currentColor;
  d: path("M7 19h2c1.1 0 2 .9 2 2v1h2v-1c0-1.1.9-2 2-2h2v-2H7z");
}

</style>
