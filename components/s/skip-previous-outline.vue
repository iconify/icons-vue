<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abr759vxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:skip-previous-outline" /></template>
<style>
.abr759vxj {
  fill: currentColor;
  d: path("M6.73 16.616V7.385h1v9.23zm10.54 0L10.345 12l6.923-4.615zm-1-1.866v-5.5L12.138 12z");
}

</style>
