<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bts7pnzsx"/><path class="fwsd42b0s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:qr-label" /></template>
<style>
.bts7pnzsx {
  d: path("M4 3.5h16v17H4Z");
}

.fwsd42b0s {
  d: path("M7.5 7H11v3.5H7.5ZM13 7h3.5v3.5H13Zm-5.5 6H11v3.5H7.5Zm7.5 2h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
