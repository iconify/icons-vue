<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGPInLSbqP)" class="r4i437pya"/><path clip-rule="evenodd" class="c5hwedbyp"/></g><defs><linearGradient id="SVGPInLSbqP" x1="5.6" x2="17.657" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop offset=".27" class="bbb5m31wc"/><stop offset="1" class="nwlphxbuq"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:saitama-background" /></template>
<style>
.bbb5m31wc {
  stop-color: var(--svg-color--2f239f, #2f239f);
}

.c5hwedbyp {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M7.52 4a8.84 8.84 0 0 0 0 6.107l.028.037l-1.49 1.28l2.01 1.312L5.6 14.935l3.342 2.011L9.646 20l2.285-2.039L14.31 20l.717-3.054l3.374-2.011l-2.464-2.18l2.007-1.331l-1.5-1.27l.042-.047c.411-.964.987-3.542 0-6.107L13.43 7.616a2.65 2.65 0 0 0-1.445-.416c-.64 0-1.16.22-1.44.389zm-.37 10.738l1.687-1.504l1.005.654l.448 1.54h3.32l.484-1.453l1.188-.791l-.155.137l1.723 1.417l-2.624 1.6l-.416 1.993l-1.883-1.513l-1.75 1.509l-.531-1.993l-2.496-1.6zm6.985-1.906l2.272-1.509l-2.647-2.272l-.366 1.646zm-1.147-4.389a2.1 2.1 0 0 0-1.002-.27c-.439 0-.809.156-1.06.312l.557 2.335l-.886 2.68l.384 1.014h.562v-1.371h.914v1.371h.476l.36-1.015l-.863-2.679zm-2.821.659l-2.615 2.221l2.304 1.468l.695-2.098zm-.302-.951l-1.81-2.14c-.119.357-.183 1.006-.17 1.646c.015.668.16 1.358.412 1.838zm4.243.032l1.581 1.335a4.2 4.2 0 0 0 .425-1.888c0-.553-.077-1.047-.137-1.417l-.032-.202z");
}

.ft5dv1b6b {
  fill: none;
}

.nwlphxbuq {
  stop-color: var(--svg-color--81bbe3, #81bbe3);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
