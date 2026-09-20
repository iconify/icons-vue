<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ial2clb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:reviews-outline-sharp" /></template>
<style>
.ial2clb2r {
  fill: currentColor;
  d: path("M9.517 13.673L12 12.167l2.483 1.506l-.66-2.825l2.196-1.884l-2.886-.256L12 6.058l-1.133 2.65l-2.886.256l2.196 1.884zM3 20.077V3h18v14H6.077zM5.65 16H20V4H4v13.644zM4 16V4z");
}

</style>
