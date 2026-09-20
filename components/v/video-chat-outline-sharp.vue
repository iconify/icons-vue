<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="th2ayxjkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:video-chat-outline-sharp" /></template>
<style>
.th2ayxjkr {
  fill: currentColor;
  d: path("M7.5 13.5h7v-2.961l1.923 1.923V7.539L14.5 9.46V6.5h-7zM3 20.077V3h18v14H6.077zM5.65 16H20V4H4v13.644zM4 16V4z");
}

</style>
