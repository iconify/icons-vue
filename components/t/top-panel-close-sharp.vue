<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ug3jopbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:top-panel-close-sharp" /></template>
<style>
.ug3jopbdm {
  fill: currentColor;
  d: path("M8.827 15.596h6.346L12 12.404zM5 19h14V9H5zm-1 1V4h16v16z");
}

</style>
