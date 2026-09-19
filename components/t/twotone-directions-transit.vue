<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kf5e48rwn"/><path class="s48nufbbl"/><circle class="iw6nvx_mx"/><circle class="cbwjarblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-directions-transit" /></template>
<style>
.cbwjarblr {
  cx: 15.5px;
  cy: 14.5px;
  r: 1.5px;
  fill: currentColor;
}

.iw6nvx_mx {
  cx: 8.5px;
  cy: 14.5px;
  r: 1.5px;
  fill: currentColor;
}

.kf5e48rwn {
  fill: currentColor;
  d: path("M12 4c-3.51 0-4.96.48-5.57 1h11.23c-.54-.54-1.95-1-5.66-1M7.5 17h9c.83 0 1.5-.67 1.5-1.5V12H6v3.5c0 .83.67 1.5 1.5 1.5m8-4c.83 0 1.5.67 1.5 1.5s-.67 1.5-1.5 1.5s-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5m-7 0c.83 0 1.5.67 1.5 1.5S9.33 16 8.5 16S7 15.33 7 14.5S7.67 13 8.5 13");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.s48nufbbl {
  fill: currentColor;
  d: path("M4 6v9.5C4 17.43 5.57 19 7.5 19L6 20.5v.5h12v-.5L16.5 19c1.93 0 3.5-1.57 3.5-3.5V6c0-3.5-3.58-4-8-4c-4 0-8 .5-8 4m14 4h-5V7h5zm-6-6c3.71 0 5.12.46 5.66 1H6.43c.61-.52 2.06-1 5.57-1M6 7h5v3H6zm0 5h12v3.5c0 .83-.67 1.5-1.5 1.5h-9c-.83 0-1.5-.67-1.5-1.5z");
}

</style>
