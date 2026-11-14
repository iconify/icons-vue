<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mt11ax_ma"/><path class="v7oq4yanq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:speaker-off" /></template>
<style>
.mt11ax_ma {
  d: path("M6.4 2.5H19v12.6m-1.4 6.4H5V8.9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v7oq4yanq {
  d: path("M8.919 12.84q-.206.383-.313.804q-.106.421-.106.856q0 .172.017.343t.05.34q.034.168.084.333t.115.323q.066.159.147.311t.177.294t.204.276q.11.133.231.255q.122.121.255.231q.133.109.276.204q.142.096.294.177t.311.147t.323.115t.333.084q.169.033.34.05T12 18q.438 0 .862-.108q.425-.108.809-.317m-1.117-8.954q.078-.039.149-.088q.072-.049.137-.107q.064-.059.12-.125q.056-.067.102-.141t.081-.154q.035-.079.059-.163t.036-.17t.012-.173q0-.061-.006-.123q-.006-.061-.018-.121t-.03-.119t-.041-.115q-.024-.057-.053-.111t-.063-.105t-.073-.099t-.082-.091q-.044-.043-.091-.082t-.099-.073t-.105-.063t-.111-.053q-.056-.023-.115-.041t-.119-.03t-.121-.018T12 6.25q-.169 0-.332.045t-.309.132t-.262.209t-.197.271M3.5 3.5l17 17");
}

</style>
