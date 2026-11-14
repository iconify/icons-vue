<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_80uabnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:solar-production" /></template>
<style>
.c_80uabnt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.037 13H4.614q-.09 0-.178-.011q-.089-.01-.176-.031q-.087-.022-.171-.053t-.164-.072t-.153-.092q-.075-.05-.142-.109q-.068-.058-.128-.125q-.06-.066-.112-.139t-.094-.152q-.043-.078-.076-.162q-.033-.083-.056-.169t-.036-.176q-.012-.088-.014-.178q-.002-.089.007-.179q.009-.089.028-.176t.049-.172l2.45-7q.038-.109.093-.212q.055-.102.124-.194q.07-.093.153-.174t.178-.148t.198-.118q.104-.052.215-.087q.11-.035.225-.053Q6.948 3 7.064 3H17.67q.083 0 .165.009q.083.009.164.027t.159.046t.154.062q.075.036.145.079q.071.044.136.095t.125.109q.059.058.112.122t.098.134t.082.143q.038.074.066.152t.049.159q.02.08.032.162q.011.082.013.165t-.006.166q-.007.083-.023.164l-1.4 7q-.045.225-.155.427M10 13v7.5M4.25 8H18.5m-8-5l-3 10M15 3l-2.5 10m5.5 8v-6m-2.5 2.5L18 15l2.5 2.5");
}

</style>
