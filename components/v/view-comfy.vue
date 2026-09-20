<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysjq_vkpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-comfy" /></template>
<style>
.ysjq_vkpb {
  fill: currentColor;
  d: path("M3 11.5V5h18v6.5zM9.385 19v-6.5H21V19zM3 19v-6.5h5.385V19z");
}

</style>
