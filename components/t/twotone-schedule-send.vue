<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbdrmfoie"/><path class="vepszya0v"/><path class="qufhvogco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-schedule-send" /></template>
<style>
.lbdrmfoie {
  fill: currentColor;
  d: path("m5 10.5l6 1.5l-6 1.5v3.49l5.39-2.27c.6-1.73 1.86-3.16 3.48-3.97L5 7.01z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.qufhvogco {
  fill: currentColor;
  d: path("M17 12c-2.76 0-5 2.24-5 5s2.24 5 5 5s5-2.24 5-5s-2.24-5-5-5m1.65 7.35L16.5 17.2V14h1v2.79l1.85 1.85z");
}

.vepszya0v {
  fill: currentColor;
  d: path("m11 12l-6-1.5V7.01l8.87 3.74c.94-.47 2-.75 3.13-.75c.1 0 .19.01.28.01L3 4v16l7-2.95V17c0-.8.14-1.56.39-2.28L5 16.99V13.5z");
}

</style>
