<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lmmqgeblg"/><path class="k5ed24v8m"/><path class="ysee5eahq"/><path class="vn1tubcoy"/><path class="on4653lnb"/><path class="odqs-5uvv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nexo" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k5ed24v8m {
  fill: var(--svg-color--2853c3, #2853c3);
  d: path("m16.496 4.4l-4.499 2.53l4.499 2.531z");
}

.lmmqgeblg {
  fill: var(--svg-color--3ca9e5, #3ca9e5);
  d: path("m7.671 4.502l8.817 4.961v5.063L3 6.939l4.325-2.43a.37.37 0 0 1 .346 0z");
}

.odqs-5uvv {
  fill: var(--svg-color--3ca9e5, #3ca9e5);
  d: path("m7.499 19.593l4.499-2.53l-4.499-2.539z");
}

.on4653lnb {
  fill: var(--svg-color--60beff, #60beff);
  d: path("M3 6.93v9.93a.35.35 0 0 0 .173.31l4.325 2.43V9.463z");
}

.vn1tubcoy {
  fill: var(--svg-color--2853c3, #2853c3);
  d: path("m21 17.059l-4.332 2.433a.37.37 0 0 1-.367 0L7.484 14.53V9.456z");
}

.ysee5eahq {
  fill: var(--svg-color--1a4199, #1a4199);
  d: path("m16.494 4.4l4.325 2.43a.35.35 0 0 1 .173.297v9.929l-4.498-2.525z");
}

</style>
