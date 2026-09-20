<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgbslzb_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:playlist-add-sharp" /></template>
<style>
.wgbslzb_x {
  fill: currentColor;
  d: path("M3.5 15.5v-1h7v1zm0-4v-1h11v1zm0-4v-1h11v1zm13 12v-4h-4v-1h4v-4h1v4h4v1h-4v4z");
}

</style>
