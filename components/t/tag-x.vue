<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l88hydb-o"/><path class="j9ertm8ro"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tag-x" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j9ertm8ro {
  d: path("M6.25 7.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m9.25 7.75l5 5m0-5l-5 5");
}

.l88hydb-o {
  d: path("M12.735 19.902q-.287.026-.573-.011t-.557-.135t-.514-.253t-.447-.359l-6.875-6.875q-.183-.183-.326-.398t-.243-.454q-.099-.238-.15-.492q-.05-.253-.05-.512V5.625q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25T3.2 4.62q.049-.119.11-.232t.132-.221t.154-.207t.173-.191t.191-.173q.099-.082.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037Q5.496 3 5.625 3h4.788q.259 0 .512.05q.254.051.492.15q.239.099.454.243q.215.143.398.326l6.875 6.875q.209.209.366.459q.158.251.255.53q.098.279.131.572q.033.294 0 .588");
}

</style>
