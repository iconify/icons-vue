<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csp0rcckc"/><path class="gax-905qg"/><path class="pausntbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-inventory" /></template>
<style>
.csp0rcckc {
  fill: currentColor;
  d: path("m21 11.5l1.5 1.5l-6.99 7L11 15.5l1.5-1.5l3.01 3z");
}

.gax-905qg {
  fill: currentColor;
  d: path("M17 5v3H7V5H5v14h6.68l-3.51-3.5l4.33-4.33l3.01 3l3.49-3.5V5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.pausntbsr {
  fill: currentColor;
  d: path("M5 19V5h2v3h10V5h2v5.67l2-2V5c0-1.1-.9-2-2-2h-4.18C14.4 1.84 13.3 1 12 1s-2.4.84-2.82 2H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h8.68l-2-2zm7-16c.55 0 1 .45 1 1s-.45 1-1 1s-1-.45-1-1s.45-1 1-1");
}

</style>
