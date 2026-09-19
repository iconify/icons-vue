<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wczhuabzy"/><circle class="sblca8zqp"/><path class="u0mdfzbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-streetview" /></template>
<style>
.sblca8zqp {
  cx: 18px;
  cy: 6px;
  r: 5px;
  fill: currentColor;
}

.u0mdfzbsk {
  fill: currentColor;
  d: path("M11.5 6c0-1.08.27-2.1.74-3H5c-1.1 0-2 .9-2 2v14c0 .55.23 1.05.59 1.41l9.82-9.82A6.44 6.44 0 0 1 11.5 6");
}

.wczhuabzy {
  fill: currentColor;
  d: path("M12.56 14.33c-.34.27-.56.7-.56 1.17V21h7c1.1 0 2-.9 2-2v-5.98c-.94-.33-1.95-.52-3-.52c-2.03 0-3.93.7-5.44 1.83");
}

</style>
