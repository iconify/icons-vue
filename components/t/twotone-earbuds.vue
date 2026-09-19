<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-ck7iysc"/><path class="g6r32ibgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-earbuds" /></template>
<style>
.g6r32ibgl {
  fill: currentColor;
  d: path("M16 3c-2.76 0-5 2.24-5 5v8c0 1.66-1.34 3-3 3s-3-1.34-3-3V9h.83C7.44 9 8.89 7.82 9 6.21A3 3 0 0 0 6.2 3C4.44 2.89 3 4.42 3 6.19V16c0 2.76 2.24 5 5 5s5-2.24 5-5V8c0-1.66 1.34-3 3-3s3 1.34 3 3v7h-.83c-1.61 0-3.06 1.18-3.17 2.79A3 3 0 0 0 17.8 21c1.76.12 3.2-1.42 3.2-3.18V8c0-2.76-2.24-5-5-5M5 6c0-.55.45-1 1-1s1 .45 1 1s-.45 1-1 1H5zm14 12c0 .55-.45 1-1 1s-1-.45-1-1s.45-1 1-1h1z");
}

.n-ck7iysc {
  fill: currentColor;
  d: path("M7 6c0-.55-.45-1-1-1s-1 .45-1 1v1h1c.55 0 1-.45 1-1m10 12c0 .55.45 1 1 1s1-.45 1-1v-1h-1c-.55 0-1 .45-1 1");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
