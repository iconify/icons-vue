<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nlh3b6xpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stack-star-sharp" /></template>
<style>
.nlh3b6xpn {
  fill: currentColor;
  d: path("M13.187 17.673L15 16.567l1.814 1.106l-.485-2.08l1.596-1.36l-2.09-.18L15 12.096l-.836 1.957l-2.089.18l1.596 1.36zM6.616 14v1H3V3h12v3.616h-1V4H4v10zM9 21V9h12v12z");
}

</style>
