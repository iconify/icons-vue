<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djpqgkr8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:policy-document" /></template>
<style>
.djpqgkr8z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 12.58V5.125q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25T4.2 4.12q.049-.119.11-.232t.132-.221t.154-.207t.173-.191t.191-.173q.099-.082.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037q.128-.013.257-.013h8.75q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087t.232.11q.114.061.221.132q.108.072.207.154q.1.082.191.173t.173.191t.154.207t.132.221t.11.232q.05.12.087.243t.063.25q.025.126.037.255q.013.128.013.257v4.432m-.215 10.359q-.076.175-.176.338q-.101.162-.224.309q-.123.146-.265.273t-.303.232q-.16.105-.333.186t-.356.136t-.373.082t-.38.028h-5.164M7 6h8M7 9.25h8M3.707 15.462l15.65-3.326a1.5 1.5 0 0 1 1.779 1.155l.312 1.467a1.5 1.5 0 0 1-1.155 1.78l-15.65 3.326a1.5 1.5 0 0 1-1.779-1.155l-.312-1.467a1.5 1.5 0 0 1 1.155-1.78m1.956-.415l.416 1.956m2.519-2.58l.312 1.467m2.622-2.091l.416 1.956m2.519-2.58l.312 1.468m2.622-2.091l.416 1.956");
}

</style>
