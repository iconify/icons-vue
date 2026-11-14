<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abcp82b_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:matcha-powder" /></template>
<style>
.abcp82b_o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.869 2.259L3.761 4.482q-1.879.684-1.195 2.563q.284.779 1.035 1.13t1.53.066l6.108-2.223q1.879-.684 1.195-2.563q-.284-.779-1.035-1.129q-.751-.351-1.53-.067M12 7.75q1 0 1.885.042l4.042-4.776q.048-.057.106-.103t.123-.08q.066-.034.137-.054t.145-.026q.073-.007.147.002q.073.008.143.031q.071.022.135.058t.121.083q.114.097.183.229q.068.133.08.282q.013.148-.033.29q-.045.143-.141.256l-3.348 3.957Q20.75 8.537 20.75 11v7.5q0 3.25-3.25 3.25h-11q-3.25 0-3.25-3.25V11q0-3.25 8.75-3.25M4.75 18.5q0 1.75 1.75 1.75h11q1.75 0 1.75-1.75v-5.366Q17.127 14.25 12 14.25t-7.25-1.116z");
}

</style>
