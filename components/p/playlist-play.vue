<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvgtrdz5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:playlist-play" /></template>
<style>
.qvgtrdz5k {
  fill: currentColor;
  d: path("M4 15.77v-1h7.02v1zm0-4v-1h10.962v1zm0-4v-1h10.962v1zM16.442 20v-5.942l4.577 2.98z");
}

</style>
