<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vwmlaebgu"/><path class="wk4sz6y2m"/><path class="p729d28_p"/><path class="onkku8bpx"/><path class="w1pk7vbcc"/><path class="zky2bubte"/><path class="tdgol74-x"/><path class="w232pxbwf"/><path class="q0ig1sbsb"/><path class="o57-6h_dn"/><path class="wx0mx5rbb"/><path class="v1t7o_bdt"/><path class="ur0pt9ypz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:srx" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.o57-6h_dn {
  fill: var(--svg-color--e23c25, #e23c25);
  d: path("M4 12V7.5l4 2.25zm0 4.5V12l4 2.25z");
}

.onkku8bpx {
  fill: var(--svg-color--e23c25, #e23c25);
  d: path("M20 16.5V12l-4 2.25zm-4-2.25v-4.5L12 12zm0 4.5v-4.5l-4 2.25z");
}

.p729d28_p {
  fill: var(--svg-color--a62222, #a62222);
  d: path("M8 18.75v-4.5L4 16.5z");
}

.q0ig1sbsb {
  fill: var(--svg-color--fac211, #fac211);
  d: path("M8 14.25v-4.5L12 12zM12 21v-4.5l4 2.25z");
}

.tdgol74-x {
  fill: var(--svg-color--ee8622, #ee8622);
  d: path("M12 7.5V3L8 5.25z");
}

.ur0pt9ypz {
  fill: var(--svg-color--a62222, #a62222);
  d: path("M16 18.75v-4.5l4 2.25z");
}

.v1t7o_bdt {
  fill: var(--svg-color--ee8622, #ee8622);
  d: path("M16 9.75v-4.5l4 2.25zm0 4.5v-4.5L20 12z");
}

.vwmlaebgu {
  fill: var(--svg-color--a62222, #a62222);
  d: path("M8 9.75v-4.5L4 7.5z");
}

.w1pk7vbcc {
  fill: var(--svg-color--ee8622, #ee8622);
  d: path("M12 21v-4.5l-4 2.25z");
}

.w232pxbwf {
  fill: var(--svg-color--e23c25, #e23c25);
  d: path("M8 9.75v-4.5l4 2.25z");
}

.wk4sz6y2m {
  fill: var(--svg-color--ee8622, #ee8622);
  d: path("M8 14.25v-4.5L4 12z");
}

.wx0mx5rbb {
  fill: var(--svg-color--fac211, #fac211);
  d: path("M12 7.5V3l4 2.25z");
}

.zky2bubte {
  fill: var(--svg-color--fac211, #fac211);
  d: path("M20 12V7.5l-4 2.25z");
}

</style>
