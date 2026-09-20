<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="zpt36xptm"/><path class="h8y6dl2xk"/><circle class="r7cjibb2o"/><circle class="ceh4jubyk"/><circle class="rh0m0lm3b"/><circle class="fec_atbaj"/><path class="q5jy1lbja"/><path class="o4093b14b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:sport-utility-vehicle" /></template>
<style>
.ceh4jubyk {
  cx: 9px;
  cy: 31px;
  r: 2px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
}

.fec_atbaj {
  cx: 27px;
  cy: 31px;
  r: 2px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
}

.h8y6dl2xk {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M5 31h26c1 0 3-1 3-4c0-2 0-8-1-9s0-7-4-7H15c-3 0-6 7-6 7l-4 1s-4 1-4 4v3s-1 .338-1 1.957S1 30 1 30z");
}

.o4093b14b {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M32 23.5a1.5 1.5 0 0 1-1.5 1.5h-22a1.5 1.5 0 1 1 0-3h22a1.5 1.5 0 0 1 1.5 1.5");
}

.q5jy1lbja {
  fill: var(--svg-color--bbddf5, #bbddf5);
  d: path("M24 17a1 1 0 0 0 1 1h4a1 1 0 0 0 1-1v-3a1 1 0 0 0-1-1h-4a1 1 0 0 0-1 1zm-11 0c0 1 .448 1 1 1h7a1 1 0 0 0 1-1v-3a1 1 0 0 0-1-1h-5c-1 0-3 3-3 4");
}

.r7cjibb2o {
  cx: 9px;
  cy: 31px;
  r: 4px;
  fill: var(--svg-color--292f33, #292f33);
}

.rh0m0lm3b {
  cx: 27px;
  cy: 31px;
  r: 4px;
  fill: var(--svg-color--292f33, #292f33);
}

.zpt36xptm {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M36 24a1 1 0 0 1-1 1h-1a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1h1a1 1 0 0 1 1 1z");
}

</style>
