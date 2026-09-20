<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8lyp9b7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:page-header-outline-sharp" /></template>
<style>
.d8lyp9b7s {
  fill: currentColor;
  d: path("M4 5V4h16v1zm0 15V7.385h16V20zm1-1h14V8.385H5zm0 0V8.385z");
}

</style>
