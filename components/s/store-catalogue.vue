<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="am7l2cbkz"/><path class="c5v1215xs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:store-catalogue" /></template>
<style>
.am7l2cbkz {
  d: path("M12 6C9.5 4.5 6 4 2.5 4.5v15c3.5-.5 7 0 9.5 1.5c2.5-1.5 6-2 9.5-1.5v-15C18 4 14.5 4.5 12 6m0 0v15M5 9.5h4.5M5 13h4.5");
}

.c5v1215xs {
  d: path("M17.081 7.75h1.169a1.5 1.5 0 0 1 1.5 1.5v6a1.5 1.5 0 0 1-1.5 1.5h-1.169a1.5 1.5 0 0 1-1.423-1.026l-1-3a1.5 1.5 0 0 1 0-.948l1-3a1.5 1.5 0 0 1 1.423-1.026m-.581 4.5h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
