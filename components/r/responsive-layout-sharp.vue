<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="liivd0vpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:responsive-layout-sharp" /></template>
<style>
.liivd0vpq {
  fill: currentColor;
  d: path("M15 20V9H9.5V4H20v16zm-5.5 0V10H14v10zM4 20V10h4.5v10z");
}

</style>
