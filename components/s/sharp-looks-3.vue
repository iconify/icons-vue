<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nw_uqfb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-looks-3" /></template>
<style>
.nw_uqfb4x {
  fill: currentColor;
  d: path("M21 3H3.01v18H21zm-5.99 14H9v-2h4v-2h-2v-2h2V9H9V7h6.01z");
}

</style>
