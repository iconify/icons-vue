<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i0hxvccko"/><path class="s0qb5vbvc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:standard-cost" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i0hxvccko {
  d: path("M21 12.994V6.125q0-.129-.013-.257q-.012-.129-.037-.255q-.026-.127-.063-.25T20.8 5.12q-.049-.119-.11-.232t-.132-.221t-.154-.207t-.173-.191q-.091-.091-.191-.173q-.099-.082-.207-.154q-.107-.071-.221-.132q-.113-.061-.232-.11q-.12-.05-.243-.087t-.25-.063q-.126-.025-.255-.037q-.128-.013-.257-.013h-6.788q-.259 0-.512.05q-.254.051-.492.15q-.239.099-.454.243q-.215.143-.398.326L4.856 9.144q-.091.091-.173.191t-.153.207q-.072.107-.133.221q-.061.113-.11.233q-.049.119-.087.242t-.062.25t-.038.255t-.013.257t.013.257t.038.255t.062.25q.038.123.087.242q.049.12.11.233t.133.221q.071.107.153.207t.173.191l4.875 4.875q.183.183.398.326t.454.243q.238.099.492.15q.253.05.512.05h.388");
}

.s0qb5vbvc {
  d: path("M6.75 11a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m8 7l2 2L21 15.75");
}

</style>
