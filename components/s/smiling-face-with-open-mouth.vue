<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="tg31urbgg"/><ellipse class="tokgqvb4x"/><ellipse class="lf9lpdb0x"/><path class="pbymswdsq"/><path class="mu3hjibwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:smiling-face-with-open-mouth" /></template>
<style>
.lf9lpdb0x {
  cx: 24.5px;
  cy: 12.5px;
  fill: var(--svg-color--664500, #664500);
  rx: 2.5px;
  ry: 5.5px;
}

.mu3hjibwp {
  fill: var(--svg-color--fff, #fff);
  d: path("M9 23s3 1 9 1s9-1 9-1s-2 4-9 4s-9-4-9-4");
}

.pbymswdsq {
  fill: var(--svg-color--664500, #664500);
  d: path("M18 22c-3.623 0-6.027-.422-9-1c-.679-.131-2 0-2 2c0 4 4.595 9 11 9c6.404 0 11-5 11-9c0-2-1.321-2.132-2-2c-2.973.578-5.377 1-9 1");
}

.tg31urbgg {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M36 18c0 9.941-8.059 18-18 18c-9.94 0-18-8.059-18-18C0 8.06 8.06 0 18 0c9.941 0 18 8.06 18 18");
}

.tokgqvb4x {
  cx: 11.5px;
  cy: 12.5px;
  fill: var(--svg-color--664500, #664500);
  rx: 2.5px;
  ry: 5.5px;
}

</style>
