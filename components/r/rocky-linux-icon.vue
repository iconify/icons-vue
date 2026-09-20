<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="i--kw23hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:rocky-linux-icon" /></template>
<style>
.i--kw23hn {
  fill: var(--svg-color--10b981, #10b981);
  d: path("M248.877 170.21C253.492 156.996 256 142.79 256 128C256 57.307 198.692 0 128 0S0 57.307 0 128c0 34.979 14.03 66.681 36.77 89.784l129.84-129.84L198.668 120zm-23.381 40.73l-58.885-58.884l-92.214 92.213C90.703 251.8 108.86 256 128 256c39.05 0 74.019-17.488 97.496-45.06");
}

</style>
