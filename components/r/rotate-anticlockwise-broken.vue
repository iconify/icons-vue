<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f1axp0vuo"/><path class="atf9vvbih"/><path class="s796clb9v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rotate-anticlockwise-broken" /></template>
<style>
.atf9vvbih {
  d: path("M6.5 10.0066C4.6403 10.0335 3.586 10.1714 2.8787 10.8788C2 11.7574 2 13.1717 2 16.0001C2 18.8285 2 20.2427 2.8787 21.1214C3.586 21.8287 4.6403 21.9667 6.5 21.9936");
}

.f1axp0vuo {
  d: path("M22 14V16C22 18.8284 22 20.2427 21.1213 21.1213C20.2426 22 18.8284 22 16 22H16H15H15C12.1716 22 10.7574 22 9.8787 21.1213C9 20.2427 9 18.8284 9 16V8C9 5.1716 9 3.7574 9.8787 2.8787C10.7574 2 12.1716 2 15 2H16C18.8284 2 20.2426 2 21.1213 2.8787C22 3.7574 22 5.1716 22 8V10");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s796clb9v {
  stroke-linejoin: round;
  d: path("M3.5 6.986L2 8C2 4.9853 4.1623 2.4828 7 2");
}

</style>
