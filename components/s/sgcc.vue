<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="fmn8yub-d"><path class="rs-j0qbjd"/><path class="kig9p6bsg"/><path class="qr_9jebzo"/><path class="yxsmxzubo"/><path class="c1yf1k7lf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sgcc" /></template>
<style>
.c1yf1k7lf {
  d: path("M23.045 5.367C11.32 16.82 15.495 40.11 27.647 45.01");
}

.fmn8yub-d {
  fill: none;
  stroke: currentColor;
  stroke-dashoffset: 3;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kig9p6bsg {
  d: path("M5.721 26.149c8.684 7.815 32.043 7.463 39.565-4.168");
}

.qr_9jebzo {
  d: path("M2.91 27.98c4.704 8.668 27.7 12.373 39.97 2.378");
}

.rs-j0qbjd {
  d: path("M45.5 24A21.5 21.5 0 0 1 24 45.5A21.5 21.5 0 0 1 2.5 24A21.5 21.5 0 0 1 24 2.5A21.5 21.5 0 0 1 45.5 24");
}

.yxsmxzubo {
  d: path("M17.56 42.298C5.835 30.845 10.01 7.556 22.162 2.656");
}

</style>
