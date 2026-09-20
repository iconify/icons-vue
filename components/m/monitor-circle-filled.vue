<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGtni5nd9O"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path clip-rule="evenodd" class="qjt6aqblq"/><path class="uyx0_-bap"/><path clip-rule="evenodd" class="rky6_ypal"/><path class="bh8sxknmt"/><path clip-rule="evenodd" class="owa4l2cof"/></g></mask></defs><circle mask="url(#SVGtni5nd9O)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:monitor-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.bh8sxknmt {
  d: path("M8.5 22.5a1 1 0 1 1 0-2h9a1 1 0 1 1 0 2z");
}

.ft5dv1b6b {
  fill: none;
}

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.owa4l2cof {
  fill-rule: evenodd;
  d: path("M22 15H4v-1h18z");
}

.qjt6aqblq {
  fill-rule: evenodd;
  d: path("M20.5 4h-15A2.5 2.5 0 0 0 3 6.5v10A2.5 2.5 0 0 0 5.5 19h15a2.5 2.5 0 0 0 2.5-2.5v-10A2.5 2.5 0 0 0 20.5 4M5 6.5a.5.5 0 0 1 .5-.5h15a.5.5 0 0 1 .5.5v10a.5.5 0 0 1-.5.5h-15a.5.5 0 0 1-.5-.5z");
}

.rky6_ypal {
  fill-rule: evenodd;
  d: path("M14.5 17.5h-3a1 1 0 0 0-1 1V21a1 1 0 0 0 1 1h3a1 1 0 0 0 1-1v-2.5a1 1 0 0 0-1-1m-2.5 3V19h2v1.5z");
}

.uyx0_-bap {
  d: path("M13 16.75a.75.75 0 1 1 0-1.5a.75.75 0 0 1 0 1.5");
}

</style>
