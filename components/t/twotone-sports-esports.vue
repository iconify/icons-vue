<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0ki3ybvq"/><path class="zf1104b_r"/><path class="l4h0pjb1g"/><circle class="on4fre1ek"/><circle class="t4ulnobzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-sports-esports" /></template>
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

.z0ki3ybvq {
  fill: currentColor;
  d: path("M16.53 7H7.47c-.99 0-1.84.74-1.98 1.72L4.4 16.37c-.03.21.05.35.13.44c.07.09.2.19.41.19c.15 0 .29-.06.39-.16L8.17 14h7.66l2.84 2.84c.1.1.24.16.39.16c.21 0 .34-.1.42-.19a.52.52 0 0 0 .13-.44l-1.09-7.66c-.15-.97-1-1.71-1.99-1.71M11 11H9v2H8v-2H6v-1h2V8h1v2h2zm4-1c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1m2 3c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.zf1104b_r {
  fill: currentColor;
  d: path("m21.58 16.09l-1.09-7.66A3.996 3.996 0 0 0 16.53 5H7.47C5.48 5 3.79 6.46 3.51 8.43l-1.09 7.66a2.545 2.545 0 0 0 4.32 2.16L9 16h6l2.25 2.25c.48.48 1.13.75 1.8.75c1.56 0 2.75-1.37 2.53-2.91m-2.1.72a.54.54 0 0 1-.42.19c-.15 0-.29-.06-.39-.16L15.83 14H8.17l-2.84 2.84c-.1.1-.24.16-.39.16a.54.54 0 0 1-.42-.19a.52.52 0 0 1-.13-.44l1.09-7.66C5.63 7.74 6.48 7 7.47 7h9.06c.99 0 1.84.74 1.98 1.72l1.09 7.66c.03.2-.05.34-.12.43");
}

</style>
