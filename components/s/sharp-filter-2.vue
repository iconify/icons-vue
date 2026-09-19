<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cb2y9vb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-filter-2" /></template>
<style>
.cb2y9vb3p {
  fill: currentColor;
  d: path("M3 5H1v18h18v-2H3zm20-4H5v18h18zm-2 16H7V3h14zm-4-4h-4v-2h4V5h-6v2h4v2h-4v6h6z");
}

</style>
