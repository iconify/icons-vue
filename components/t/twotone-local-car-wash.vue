<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqegygr-g"/><path class="fky34obul"/><circle class="dr36jwb_v"/><circle class="a8opedcca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-local-car-wash" /></template>
<style>
.a8opedcca {
  cx: 16.5px;
  cy: 16.5px;
  r: 1.5px;
  fill: currentColor;
}

.dr36jwb_v {
  cx: 7.5px;
  cy: 16.5px;
  r: 1.5px;
  fill: currentColor;
}

.fky34obul {
  fill: currentColor;
  d: path("M15.5 3.5c0 .83.67 1.5 1.5 1.5s1.5-.67 1.5-1.5c0-1-1.5-2.7-1.5-2.7s-1.5 1.7-1.5 2.7m-2 0c0-1-1.5-2.7-1.5-2.7s-1.5 1.7-1.5 2.7c0 .83.67 1.5 1.5 1.5s1.5-.67 1.5-1.5m-5 0C8.5 2.5 7 .8 7 .8S5.5 2.5 5.5 3.5C5.5 4.33 6.17 5 7 5s1.5-.67 1.5-1.5M21 14l-2.08-5.99C18.72 7.42 18.16 7 17.5 7h-11c-.66 0-1.21.42-1.42 1.01L3 14v8c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-1h12v1c0 .55.45 1 1 1h1c.55 0 1-.45 1-1zM6.85 9h10.29l1.04 3H5.81zM19 19H5v-4.66l.12-.34h13.77l.11.34z");
}

.iqegygr-g {
  fill: currentColor;
  d: path("m5.12 14l-.12.34V19h14v-4.66l-.12-.34zm2.38 4c-.83 0-1.5-.67-1.5-1.5S6.67 15 7.5 15s1.5.67 1.5 1.5S8.33 18 7.5 18m9 0c-.83 0-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5s1.5.67 1.5 1.5s-.67 1.5-1.5 1.5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
