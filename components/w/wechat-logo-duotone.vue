<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="ltqwa_bcq"/><path class="ix3m34zyd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:wechat-logo-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ix3m34zyd {
  d: path("M144 140a12 12 0 1 1-12-12a12 12 0 0 1 12 12m44-12a12 12 0 1 0 12 12a12 12 0 0 0-12-12m51.34 83.47a16 16 0 0 1-19.87 19.87l-24.71-7.27a80 80 0 0 1-108.33-40.65a79 79 0 0 1-25.19-7.35l-24.71 7.27a16 16 0 0 1-19.87-19.87l7.27-24.71a80 80 0 1 1 145.65-66.17a80 80 0 0 1 62.49 114.17ZM81.3 166.3a79.94 79.94 0 0 1 70.38-93.87a64 64 0 0 0-112.13 61.76a8 8 0 0 1 .63 6L32 168l27.76-8.17a8 8 0 0 1 6 .63a63.5 63.5 0 0 0 15.54 5.84m135.15 15.89a64 64 0 1 0-26.26 26.26a8 8 0 0 1 6-.63L224 216l-8.17-27.76a8 8 0 0 1 .62-6.05");
}

.ltqwa_bcq {
  d: path("M163.94 80.11C162.63 80 161.32 80 160 80a72 72 0 0 0-67.93 95.88a71.5 71.5 0 0 1-30-8.39l-27.76 8.16a8 8 0 0 1-9.93-9.93L32.5 138a72 72 0 1 1 131.44-57.89");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
