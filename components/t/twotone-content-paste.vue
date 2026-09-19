<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sa88ynbuz"/><path class="ek4z-nb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-content-paste" /></template>
<style>
.ek4z-nb4d {
  fill: currentColor;
  d: path("M19 2h-4.18C14.4.84 13.3 0 12 0S9.6.84 9.18 2H5c-1.1 0-2 .9-2 2v16c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m-7 0c.55 0 1 .45 1 1s-.45 1-1 1s-1-.45-1-1s.45-1 1-1m7 18H5V4h2v3h10V4h2z");
}

.sa88ynbuz {
  fill: currentColor;
  d: path("M17 7H7V4H5v16h14V4h-2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
