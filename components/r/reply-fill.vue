<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_-ca_wee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:reply-fill" /></template>
<style>
.h_-ca_wee {
  fill: currentColor;
  d: path("M5.414 8H19a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3h-8a1 1 0 0 1 0-2h8a1 1 0 0 0 1-1v-6a1 1 0 0 0-1-1H5.414l2.293 2.293a.999.999 0 1 1-1.414 1.414l-4-4a1 1 0 0 1 0-1.414l4-4a.999.999 0 1 1 1.414 1.414Z");
}

</style>
