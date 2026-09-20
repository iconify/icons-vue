<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4y7628xu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mtl" /></template>
<style>
.e4y7628xu {
  fill: var(--svg-color--fff, #fff);
  d: path("M3 4.125h1.125v15.75H3zM8.625 7.5H9.75v10.125H8.625zm5.625 2.25h1.125v5.625H14.25zm5.625-5.625H21v15.75h-1.125z");
}

</style>
