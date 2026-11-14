<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rkdooe55p"/><path class="cj0ovgb6r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:security-badge" /></template>
<style>
.cj0ovgb6r {
  d: path("m12.625 7.875l.261.574a1.5 1.5 0 0 0 1.241.874l.623.052a.645.645 0 0 1 .375 1.125l-.46.409a1.5 1.5 0 0 0-.465 1.458l.184.795a.667.667 0 0 1-1.009.713l-.57-.363a1.5 1.5 0 0 0-1.61 0l-.57.363a.667.667 0 0 1-1.009-.713l.184-.795a1.5 1.5 0 0 0-.465-1.458l-.46-.409a.645.645 0 0 1 .375-1.125l.623-.052a1.5 1.5 0 0 0 1.241-.874l.261-.574a.687.687 0 0 1 1.25 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rkdooe55p {
  d: path("m12 2.5l7.5 3V11c0 5-3 8.5-7.5 10.5c-4.5-2-7.5-5.5-7.5-10.5V5.5Z");
}

</style>
