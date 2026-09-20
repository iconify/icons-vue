<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":320};
const content = `<path class="artwekbhw"/><path class="s9mzi_bmo"/><path class="hao8cdygu"/><path class="hk5rp4dfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:passport" /></template>
<style>
.artwekbhw {
  fill: var(--svg-color--d6ff00, #d6ff00);
  d: path("M128 0C57.28 0 0 57.28 0 128h64c0-35.328 28.672-64 64-64z");
}

.hao8cdygu {
  fill: var(--svg-color--00b9f1, #00b9f1);
  d: path("M128 256c70.72 0 128-57.28 128-128h-64c0 35.328-28.672 64-64 64z");
}

.hk5rp4dfg {
  fill: var(--svg-color--fff, #fff);
  d: path("M64 256V128H0v192h128v-64z");
}

.s9mzi_bmo {
  fill: var(--svg-color--34e27a, #34e27a);
  d: path("M256 128C256 57.28 198.72 0 128 0v64c35.328 0 64 28.672 64 64z");
}

</style>
