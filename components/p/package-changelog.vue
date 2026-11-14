<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r88ygmbxi"/><path class="g41acebvw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:package-changelog" /></template>
<style>
.g41acebvw {
  d: path("M3 6.75L11 11l8-4.25M11 11v9.25M7 4.75l8 4m.5 6.25h6m-6 3.25h6m-6 3.25H19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r88ygmbxi {
  d: path("m12.887 19.248l-1.066.566q-.19.101-.398.153t-.423.052t-.423-.052t-.398-.153l-6.25-3.32q-.105-.056-.201-.125t-.182-.151q-.086-.081-.161-.174q-.074-.092-.135-.194t-.108-.211t-.078-.223t-.048-.232T3 14.948V7.802q0-.119.016-.236q.016-.118.048-.232q.031-.114.078-.223T3.25 6.9t.135-.194q.075-.093.161-.174q.086-.082.182-.151t.201-.125l6.25-3.32q.19-.101.398-.153T11 2.731t.423.052t.398.153l6.25 3.32q.105.056.201.125t.182.151t.161.174t.135.194t.108.211t.078.223q.032.114.048.232q.016.117.016.236v4.419");
}

</style>
