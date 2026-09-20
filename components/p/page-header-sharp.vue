<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqteh8y2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:page-header-sharp" /></template>
<style>
.iqteh8y2k {
  fill: currentColor;
  d: path("M4 5V4h16v1zm0 15V7.385h16V20z");
}

</style>
