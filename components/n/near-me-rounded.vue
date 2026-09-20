<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4a346bka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:near-me-rounded" /></template>
<style>
.r4a346bka {
  fill: currentColor;
  d: path("m10.05 13.95l-6.475-2.625q-.325-.125-.475-.387t-.15-.538t.163-.537t.487-.388l15.35-5.7q.3-.125.575-.05T20 4t.275.475t-.05.575l-5.7 15.35q-.125.325-.387.488t-.538.162t-.537-.15t-.388-.475z");
}

</style>
