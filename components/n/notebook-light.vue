<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="slwhd-bwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:notebook-light" /></template>
<style>
.slwhd-bwt {
  fill: currentColor;
  d: path("M182 112a6 6 0 0 1-6 6h-64a6 6 0 0 1 0-12h64a6 6 0 0 1 6 6m-6 26h-64a6 6 0 0 0 0 12h64a6 6 0 0 0 0-12m46-90v160a14 14 0 0 1-14 14H48a14 14 0 0 1-14-14V48a14 14 0 0 1 14-14h160a14 14 0 0 1 14 14M48 210h26V46H48a2 2 0 0 0-2 2v160a2 2 0 0 0 2 2M210 48a2 2 0 0 0-2-2H86v164h122a2 2 0 0 0 2-2Z");
}

</style>
