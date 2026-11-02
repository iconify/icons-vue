<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcgi_3evl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paragraph-bulk-round" /></template>
<style>
.tcgi_3evl {
  fill: currentColor;
  d: path("M11 12V6a3 3 0 1 0 0 6m0 2a5 5 0 0 1 0-10h6a1 1 0 0 1 0 2v13a1 1 0 0 1-2 0V6h-2v13a1 1 0 0 1-2 0Z");
}

</style>
