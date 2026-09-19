<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yffecxbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-move-to-inbox" /></template>
<style>
.yffecxbmu {
  fill: currentColor;
  d: path("M21 3H3v18h18zm-2 12h-4c0 1.66-1.35 3-3 3s-3-1.34-3-3H4.99V5H19zm-3-5h-2V7h-4v3H8l4 4z");
}

</style>
