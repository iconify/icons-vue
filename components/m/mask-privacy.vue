<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-c21n57t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mask-privacy" /></template>
<style>
.n-c21n57t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 9q0-3.25 3.25-3.25h14q3.25 0 3.25 3.25v2q0 2.864-1.862 4.61q-1.75 1.64-4.388 1.64q-1.974 0-4-2.159q-2.026 2.159-4 2.159q-2.638 0-4.388-1.64Q1.75 13.864 1.75 11zm12.742 3.685q.848.566 2.008.566t2.008-.566q.993-.662.992-1.686q.001-1.022-.992-1.684q-.848-.566-2.008-.566t-2.008.566q-.992.662-.992 1.684v.002q0 1.022.992 1.684M7.5 8.75q-3 0-3 2.25t3 2.25t3-2.25t-3-2.25");
}

</style>
