<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hud-_wbev"/><path class="hdgaeqbyd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tag-check" /></template>
<style>
.hdgaeqbyd {
  d: path("M6.25 7.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M14.75 18l2 2L21 15.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hud-_wbev {
  d: path("M12.735 19.902q-.287.026-.573-.011t-.557-.135t-.514-.253t-.447-.359l-6.875-6.875q-.183-.183-.326-.398t-.243-.454q-.099-.238-.15-.492q-.05-.253-.05-.512V5.625q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25T3.2 4.62q.049-.119.11-.232t.132-.221t.154-.207t.173-.191t.191-.173q.099-.082.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037Q5.496 3 5.625 3h4.788q.259 0 .512.05q.254.051.492.15q.239.099.454.243q.215.143.398.326l6.875 6.875q.123.123.229.262q.106.138.192.289t.153.313q.066.161.11.33q.044.168.065.341t.02.347t-.027.347q-.025.172-.072.34");
}

</style>
