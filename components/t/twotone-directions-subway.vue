<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ve7z5c5ve"/><path class="l-x5dnb0u"/><circle class="iw6nvx_mx"/><circle class="cbwjarblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-directions-subway" /></template>
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

.l-x5dnb0u {
  fill: currentColor;
  d: path("M12 2c-4 0-8 .5-8 4v9.5C4 17.43 5.57 19 7.5 19L6 20.5v.5h12v-.5L16.5 19c1.93 0 3.5-1.57 3.5-3.5V6c0-3.5-3.58-4-8-4m0 2c3.71 0 5.12.46 5.66 1H6.43c.61-.52 2.06-1 5.57-1M6 7h5v3H6zm12 8.5c0 .83-.67 1.5-1.5 1.5h-9c-.83 0-1.5-.67-1.5-1.5V12h12zm0-5.5h-5V7h5z");
}

.ve7z5c5ve {
  fill: currentColor;
  d: path("M12 4c-3.51 0-4.96.48-5.57 1h11.23c-.54-.54-1.95-1-5.66-1M6 15.5c0 .83.67 1.5 1.5 1.5h9c.83 0 1.5-.67 1.5-1.5V12H6zm9.5-2.5c.83 0 1.5.67 1.5 1.5s-.67 1.5-1.5 1.5s-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5m-7 0c.83 0 1.5.67 1.5 1.5S9.33 16 8.5 16S7 15.33 7 14.5S7.67 13 8.5 13");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
