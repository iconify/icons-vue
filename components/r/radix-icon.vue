<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":393};
const content = `<path class="ky6pv2ppl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:radix-icon" /></template>
<style>
.ky6pv2ppl {
  d: path("M119.467 392.533C53.487 392.533 0 335.227 0 264.533c0-70.693 53.487-128 119.467-128zm0-392.533H0v119.467h119.467zm76.8 119.467c32.99 0 59.733-26.744 59.733-59.734S229.257 0 196.267 0s-59.734 26.743-59.734 59.733s26.744 59.734 59.734 59.734");
}

</style>
