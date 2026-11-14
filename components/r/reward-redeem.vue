<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xpwxj6b4z"/><path class="e9fltbcec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:reward-redeem" /></template>
<style>
.e9fltbcec {
  d: path("m14.75 18l2 2L21 15.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xpwxj6b4z {
  d: path("M5.25 8h13.5a1.75 1.75 0 0 1 1.75 1.75v1a1.75 1.75 0 0 1-1.75 1.75H5.25a1.75 1.75 0 0 1-1.75-1.75v-1A1.75 1.75 0 0 1 5.25 8m13.437 13.972q-.102.219-.229.424q-.128.205-.278.394t-.323.358q-.172.17-.363.318t-.398.272q-.207.125-.427.224q-.221.099-.451.171q-.231.072-.468.117q-.197.037-.396.054t-.399.015t-.398-.024t-.395-.062q-.195-.042-.386-.102t-.375-.138t-.359-.175t-.34-.209t-.318-.242q-.153-.128-.293-.271t-.265-.299t-.235-.323t-.201-.345t-.167-.363q-.074-.186-.13-.378q-.056-.191-.093-.388h1.25H6.5q-.074 0-.147-.007t-.146-.022t-.142-.036q-.071-.021-.139-.049t-.133-.063t-.126-.076t-.119-.087q-.057-.047-.109-.099t-.099-.109q-.046-.057-.087-.119t-.076-.126q-.035-.065-.063-.133t-.049-.139q-.022-.07-.036-.142q-.015-.073-.022-.146T5 19.5v-7h14v1.3M12 8v4.5M12 8c-1.5-3-5-5-5.25-2.25C6.6 7.25 9 8 12 8m0 0c1.5-3 5-5 5.25-2.25C17.4 7.25 15 8 12 8");
}

</style>
