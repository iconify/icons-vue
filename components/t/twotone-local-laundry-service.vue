<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_ifpvi1m"/><path class="w19l8-jza"/><circle class="s3cqxlbus"/><circle class="ay4kxuviq"/><path class="h_1rhebpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-local-laundry-service" /></template>
<style>
.ay4kxuviq {
  cx: 11px;
  cy: 6px;
  r: 1px;
  fill: currentColor;
}

.h_1rhebpv {
  fill: currentColor;
  d: path("M12 19c2.76 0 5-2.24 5-5s-2.24-5-5-5s-5 2.24-5 5s2.24 5 5 5m2.36-7.36c1.3 1.3 1.3 3.42 0 4.72s-3.42 1.3-4.72 0z");
}

.p_ifpvi1m {
  fill: currentColor;
  d: path("M5.99 4L6 20h12V4zc.01 0 0 0 0 0M11 5c.55 0 1 .45 1 1s-.45 1-1 1s-1-.45-1-1s.45-1 1-1M8 5c.55 0 1 .45 1 1s-.45 1-1 1s-1-.45-1-1s.45-1 1-1m4 4c2.76 0 5 2.24 5 5s-2.24 5-5 5s-5-2.24-5-5s2.24-5 5-5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.s3cqxlbus {
  cx: 8px;
  cy: 6px;
  r: 1px;
  fill: currentColor;
}

.w19l8-jza {
  fill: currentColor;
  d: path("M18 2.01L6 2c-1.11 0-2 .89-2 2v16c0 1.11.89 2 2 2h12c1.11 0 2-.89 2-2V4c0-1.11-.89-1.99-2-1.99M18 20H6L5.99 4H18z");
}

</style>
