<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ag09zkbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:reward-welcome-bonus" /></template>
<style>
.ag09zkbga {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.2 12.5H3.5V8h17v4.2m-3.443 11.562q-.611.358-1.307.488q-.197.037-.396.054t-.399.015t-.398-.024t-.395-.062q-.195-.042-.386-.102t-.375-.138t-.359-.175t-.34-.209t-.318-.242q-.153-.128-.293-.271t-.265-.299t-.235-.323t-.201-.345t-.167-.363q-.074-.186-.13-.378q-.056-.191-.093-.388h1.25H6.5q-.074 0-.147-.007t-.146-.022t-.142-.036q-.071-.021-.139-.049t-.133-.063t-.126-.076t-.119-.087q-.057-.047-.109-.099t-.099-.109q-.046-.057-.087-.119t-.076-.126q-.035-.065-.063-.133t-.049-.139q-.022-.07-.036-.142q-.015-.073-.022-.146T5 19.5v-7h10.2M12 8v4.5M12 8c-1.5-3-5-5-5.25-2.25C6.6 7.25 9 8 12 8m0 0c1.5-3 5-5 5.25-2.25C17.4 7.25 15 8 12 8m6 7v6m-3-3h6");
}

</style>
