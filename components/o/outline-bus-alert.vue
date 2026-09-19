<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="aqszcbwbb"/><circle class="j6ucgibuk"/><path class="i94_85bxh"/><path class="w9pxaxgbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-bus-alert" /></template>
<style>
.aqszcbwbb {
  cx: 6.5px;
  cy: 15.5px;
  r: 1.5px;
  fill: currentColor;
}

.i94_85bxh {
  fill: currentColor;
  d: path("M4 11V8h7.29C11.1 7.37 11 6.7 11 6H4.43c.83-.71 2.98-1.09 6.65-.98c.1-.7.3-1.37.59-1.99C2.97 2.67 2 5.02 2 7v9.5c0 .95.38 1.81 1 2.44V21c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-1h8v1c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-2.06c.62-.63 1-1.49 1-2.44V13c-1.91 0-3.63-.76-4.89-2zm12 5c0 1.1-.9 2-2 2H6c-1.1 0-2-.9-2-2v-3h12z");
}

.j6ucgibuk {
  cx: 13.5px;
  cy: 15.5px;
  r: 1.5px;
  fill: currentColor;
}

.w9pxaxgbc {
  fill: currentColor;
  d: path("M18 1c-2.76 0-5 2.24-5 5s2.24 5 5 5s5-2.24 5-5s-2.24-5-5-5m.5 8h-1V8h1zm0-2h-1V3h1z");
}

</style>
