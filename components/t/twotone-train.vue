<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6tdw1blj"/><circle class="iw6nvx_mx"/><circle class="cbwjarblr"/><path class="hpw8yvqzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-train" /></template>
<style>
.cbwjarblr {
  cx: 15.5px;
  cy: 14.5px;
  r: 1.5px;
  fill: currentColor;
}

.f6tdw1blj {
  fill: currentColor;
  d: path("M12 4c-3.51 0-4.96.48-5.57 1h11.13c-.6-.52-2.05-1-5.56-1M6 15.5c0 .83.67 1.5 1.5 1.5h9c.83 0 1.5-.67 1.5-1.5V12H6zm9.5-2.5c.83 0 1.5.67 1.5 1.5s-.67 1.5-1.5 1.5s-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5m-7 0c.83 0 1.5.67 1.5 1.5S9.33 16 8.5 16S7 15.33 7 14.5S7.67 13 8.5 13");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.hpw8yvqzr {
  fill: currentColor;
  d: path("M12 2c-4 0-8 .5-8 4v9.5C4 17.43 5.57 19 7.5 19L6 20.5v.5h2l2-2h4l2 2h2v-.5L16.5 19c1.93 0 3.5-1.57 3.5-3.5V6c0-3.5-4-4-8-4m0 2c3.51 0 4.96.48 5.57 1H6.43c.61-.52 2.06-1 5.57-1M6 7h5v3H6zm12 8.5c0 .83-.67 1.5-1.5 1.5h-9c-.83 0-1.5-.67-1.5-1.5V12h12zm0-5.5h-5V7h5z");
}

.iw6nvx_mx {
  cx: 8.5px;
  cy: 14.5px;
  r: 1.5px;
  fill: currentColor;
}

</style>
