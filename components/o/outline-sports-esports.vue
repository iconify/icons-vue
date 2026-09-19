<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zf1104b_r"/><path class="l4h0pjb1g"/><circle class="on4fre1ek"/><circle class="t4ulnobzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-sports-esports" /></template>
<style>
.l4h0pjb1g {
  fill: currentColor;
  d: path("M9 8H8v2H6v1h2v2h1v-2h2v-1H9z");
}

.on4fre1ek {
  cx: 17px;
  cy: 12px;
  r: 1px;
  fill: currentColor;
}

.t4ulnobzr {
  cx: 15px;
  cy: 9px;
  r: 1px;
  fill: currentColor;
}

.zf1104b_r {
  fill: currentColor;
  d: path("m21.58 16.09l-1.09-7.66A3.996 3.996 0 0 0 16.53 5H7.47C5.48 5 3.79 6.46 3.51 8.43l-1.09 7.66a2.545 2.545 0 0 0 4.32 2.16L9 16h6l2.25 2.25c.48.48 1.13.75 1.8.75c1.56 0 2.75-1.37 2.53-2.91m-2.1.72a.54.54 0 0 1-.42.19c-.15 0-.29-.06-.39-.16L15.83 14H8.17l-2.84 2.84c-.1.1-.24.16-.39.16a.54.54 0 0 1-.42-.19a.52.52 0 0 1-.13-.44l1.09-7.66C5.63 7.74 6.48 7 7.47 7h9.06c.99 0 1.84.74 1.98 1.72l1.09 7.66c.03.2-.05.34-.12.43");
}

</style>
