<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_dz4-bcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-minus-corner-fill-sharp" /></template>
<style>
.k_dz4-bcy {
  fill: currentColor;
  d: path("M2 20V4a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H4v10h4a1 1 0 0 1 0 2H3a1 1 0 0 1-1-1m11-5h8a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2");
}

</style>
