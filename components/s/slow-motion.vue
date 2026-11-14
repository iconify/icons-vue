<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tnpvlcxio"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:slow-motion" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tnpvlcxio {
  d: path("m12.7 15.07l-4.781 2.709q-.074.042-.152.079q-.077.038-.156.07t-.161.059t-.164.048t-.167.038t-.169.027t-.17.016t-.171.004q-.086 0-.171-.007q-.085-.006-.17-.017t-.169-.029q-.084-.017-.166-.04q-.083-.022-.164-.05t-.16-.061t-.155-.072q-.077-.038-.151-.081t-.145-.091t-.138-.1t-.132-.109t-.125-.117t-.116-.126q-.057-.064-.109-.132t-.099-.14t-.09-.145t-.08-.151t-.071-.156t-.06-.16t-.049-.164t-.039-.167t-.028-.169t-.016-.17T4 15.495v-7.99q0-.086.006-.171q.005-.085.016-.17t.028-.169t.039-.167t.049-.164t.06-.16t.071-.156t.08-.151t.09-.145t.099-.14t.109-.132q.056-.065.116-.126q.061-.06.125-.117t.132-.109t.138-.1t.145-.091t.151-.081t.155-.072t.16-.061t.164-.05t.166-.04t.169-.029t.17-.017q.085-.007.171-.007q.086-.001.171.004q.085.006.17.016t.169.027q.085.016.167.038q.083.021.164.048q.082.027.161.059t.156.07q.078.037.152.079l7.051 3.995q.151.085.289.19q.139.105.262.226t.23.259t.193.287t.154.31t.112.327t.068.34t.023.345q0 .337-.085.664M14.75 18a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

</style>
