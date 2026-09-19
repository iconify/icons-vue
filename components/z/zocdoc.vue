<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l0eom_t1n"/><circle class="p9-sh9bos"/><circle class="ucmecn-5v"/><path class="d9q8wzbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zocdoc" /></template>
<style>
.d9q8wzbwk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.768 12.324h15.804l-15.4 22.703c5.535 2.6 12.036 2.195 16.788-.27");
}

.l0eom_t1n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.803 21.203c0 16.038-.9 22.297-9.231 22.297c-9.975 0-22.375-15.1-22.375-25.27c0-7.583 6.147-13.73 13.73-13.73s17.876 5.516 17.876 16.703");
}

.p9-sh9bos {
  cx: 14.768px;
  cy: 23.92px;
  r: 1.895px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ucmecn-5v {
  cx: 31.313px;
  cy: 23.92px;
  r: 1.895px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
