<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n23sc8cvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:re-order-dots-horizontal-24-regular" /></template>
<style>
.n23sc8cvg {
  fill: currentColor;
  d: path("M7 15.5a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m0-7a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m7 7a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m0-7a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m7 7a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m0-7a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0");
}

</style>
