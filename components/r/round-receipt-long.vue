<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krfp-4lrw"/><path class="f6dk_16cf"/><circle class="clkylsyqb"/><circle class="rn2kcz5al"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-receipt-long" /></template>
<style>
.clkylsyqb {
  cx: 17px;
  cy: 8px;
  r: 1px;
  fill: currentColor;
}

.f6dk_16cf {
  fill: currentColor;
  d: path("M19.5 3.5L18 2l-1.5 1.5L15 2l-1.5 1.5L12 2l-1.5 1.5L9 2L7.5 3.5L6 2v14H4c-.55 0-1 .45-1 1v2c0 1.66 1.34 3 3 3h12c1.66 0 3-1.34 3-3V2zM15 20H6c-.55 0-1-.45-1-1v-1h10zm4-1c0 .55-.45 1-1 1s-1-.45-1-1v-2c0-.55-.45-1-1-1H8V5h11z");
}

.krfp-4lrw {
  fill: currentColor;
  d: path("M14 9h-4c-.55 0-1-.45-1-1s.45-1 1-1h4c.55 0 1 .45 1 1s-.45 1-1 1m0 3h-4c-.55 0-1-.45-1-1s.45-1 1-1h4c.55 0 1 .45 1 1s-.45 1-1 1");
}

.rn2kcz5al {
  cx: 17px;
  cy: 11px;
  r: 1px;
  fill: currentColor;
}

</style>
