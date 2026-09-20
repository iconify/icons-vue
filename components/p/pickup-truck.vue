<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="nsme2t7qm"/><circle class="r7cjibb2o"/><circle class="ceh4jubyk"/><circle class="rh0m0lm3b"/><circle class="fec_atbaj"/><path class="tdaeddixn"/><path class="be6s5jstw"/><path class="rl-5kjc3v"/><path class="eha6gcctb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:pickup-truck" /></template>
<style>
.be6s5jstw {
  fill: var(--svg-color--f492a9, #f492a9);
  d: path("M36 21.5a1.5 1.5 0 0 1-1.5 1.5H20v-3h14.5a1.5 1.5 0 0 1 1.5 1.5");
}

.ceh4jubyk {
  cx: 9px;
  cy: 31px;
  r: 2px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
}

.eha6gcctb {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M2 31H1c-.55 0-1-.45-1-1v-2c0-.55.45-1 1-1h1c.55 0 1 .45 1 1v2c0 .55-.45 1-1 1m32 0h-1c-.55 0-1-.45-1-1v-2c0-.55.45-1 1-1h1c.55 0 1 .45 1 1v2c0 .55-.45 1-1 1");
}

.fec_atbaj {
  cx: 27px;
  cy: 31px;
  r: 2px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
}

.nsme2t7qm {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M33 31c1 0 1-1 1-4c0-.692 0-3.862-.041-5.138C33.939 21.258 33.149 20 32 20H20v-6c0-1.058-.235-2-2-2h-5c-3 0-6 8-6 8s-6 0-6 3v4s-1 .338-1 1.957S1 31 2 31z");
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

.rl-5kjc3v {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M1 23h1v5H1z");
}

.tdaeddixn {
  fill: var(--svg-color--bbddf5, #bbddf5);
  d: path("M10 19c0 1 .448 1 1 1h5a1 1 0 0 0 1-1v-4a1 1 0 0 0-1-1h-3c-1 0-3 4-3 5");
}

</style>
