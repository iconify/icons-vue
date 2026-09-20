<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqstirb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stairs-outline-sharp" /></template>
<style>
.dqstirb5e {
  fill: currentColor;
  d: path("M6 18h4.425v-3.325H13V11.35h2.575V8H18V6h-4.425v3.325H11v3.325H8.425V16H6zm-3 3V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
