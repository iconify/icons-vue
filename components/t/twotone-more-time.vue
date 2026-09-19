<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yw01a-kgm"/><path class="cl8ryacye"/><path class="vd0f0bh_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-more-time" /></template>
<style>
.cl8ryacye {
  fill: currentColor;
  d: path("M17.92 12A6.957 6.957 0 0 1 11 20c-3.9 0-7-3.1-7-7s3.1-7 7-7c.7 0 1.37.1 2 .29V4.23c-.64-.15-1.31-.23-2-.23c-5 0-9 4-9 9s4 9 9 9a8.963 8.963 0 0 0 8.94-10z");
}

.vd0f0bh_w {
  fill: currentColor;
  d: path("M20 5V2h-2v3h-3v2h3v3h2V7h3V5z");
}

.yw01a-kgm {
  fill: currentColor;
  d: path("M10 8v6l4.7 2.9l.8-1.2l-4-2.4V8z");
}

</style>
