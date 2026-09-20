<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ee9ckpb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:scrollable-header-outline-sharp" /></template>
<style>
.ee9ckpb8r {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-1h14v-5.384H5zm0-6.384h14V5H5zm0 0V5z");
}

</style>
