<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fmcv5r1wu"/><path class="su7fkn_zh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tag-plus" /></template>
<style>
.fmcv5r1wu {
  d: path("M12.949 19.874q-.155.027-.312.035t-.314-.002q-.157-.011-.311-.04q-.155-.029-.305-.077q-.15-.047-.293-.112t-.277-.147t-.258-.179t-.235-.208l-6.875-6.875q-.183-.183-.326-.398t-.243-.454q-.099-.238-.15-.492q-.05-.253-.05-.512V5.625q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25T3.2 4.62q.049-.119.11-.232t.132-.221t.154-.207t.173-.191t.191-.173q.099-.082.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037Q5.496 3 5.625 3h4.788q.259 0 .512.05q.254.051.492.15q.239.099.454.243q.215.143.398.326l6.875 6.875q.109.109.204.23q.096.121.176.252q.081.132.146.271q.065.14.113.287q.047.146.078.297q.03.151.043.305q.013.153.007.307t-.029.307");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.su7fkn_zh {
  d: path("M6.25 7.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M18 15v6m-3-3h6");
}

</style>
