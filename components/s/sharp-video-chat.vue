<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gyvqrbb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-video-chat" /></template>
<style>
.gyvqrbb9m {
  fill: currentColor;
  d: path("M2 2v20l4-4h16V2zm15 11l-2-1.99V14H7V6h8v2.99L17 7z");
}

</style>
