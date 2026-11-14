<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bz-21vbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:snapshot-test" /></template>
<style>
.bz-21vbts {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7.5V5a2 2 0 0 1 2-2h2.5m9 0H19a2 2 0 0 1 2 2v2.5M7.5 21H5a2 2 0 0 1-2-2v-2.5m9.264 0H9q-.074 0-.147-.007t-.146-.022t-.142-.036q-.071-.021-.139-.049t-.133-.063t-.126-.076q-.062-.041-.119-.087q-.057-.047-.109-.099t-.099-.109q-.046-.057-.087-.119t-.076-.126t-.063-.133t-.049-.139t-.036-.142q-.015-.073-.022-.146T7.5 15V7.5q0-.074.007-.147t.022-.146q.014-.072.036-.142q.021-.071.049-.139t.063-.133t.076-.126t.087-.119q.047-.057.099-.109t.109-.099q.057-.046.119-.087t.126-.076t.133-.063t.139-.049t.142-.036q.073-.015.146-.022T9 6h3.5l3 3v5.857M14.75 18l2 2L21 15.75");
}

</style>
