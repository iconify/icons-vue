<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbihh_bwr"/><path class="y19g5joxc"/><path class="urngxsyqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-send-and-archive" /></template>
<style>
.hbihh_bwr {
  fill: currentColor;
  d: path("M5 7.01v3.49l6 1.5l-6 1.5v3.49l5.39-2.27a7 7 0 0 1 3.48-3.97z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.urngxsyqt {
  fill: currentColor;
  d: path("M17 12c-2.76 0-5 2.24-5 5s2.24 5 5 5s5-2.24 5-5s-2.24-5-5-5m0 8l-3-3h2.5v-3h1v3H20z");
}

.y19g5joxc {
  fill: currentColor;
  d: path("m11 12l-6-1.5V7.01l8.87 3.73c.94-.47 2-.75 3.13-.75c.1 0 .19.01.28.01L3 4v16l7-2.95V17c0-.8.14-1.56.39-2.28L5 16.99V13.5z");
}

</style>
