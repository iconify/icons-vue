<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q0egpm5kq"/><circle class="nmecg-b9i"/><path class="t0-b_i22p"/><path class="iw_toqivl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:miraie" /></template>
<style>
.iw_toqivl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.17 22.179v8.5h13.572v-8.5l-6.786-4.858z");
}

.nmecg-b9i {
  cx: 15.457px;
  cy: 22.929px;
  r: 0.7px;
  fill: currentColor;
}

.q0egpm5kq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.986 22.679v8M4.5 30.67v-7.991l4 8l4-7.988v7.988m5.914-3.3a2 2 0 0 1 2-2m-2 0v5.3");
}

.t0-b_i22p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.457 25.379v5.3m27.781-1.009a2 2 0 0 1-3.738-.99v-1.3a2 2 0 1 1 4 0v.65h-4m-9.149-.001h-3.544m-.878 2.65l2.65-8l2.65 8");
}

</style>
