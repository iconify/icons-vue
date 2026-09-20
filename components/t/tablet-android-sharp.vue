<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf3vm6b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tablet-android-sharp" /></template>
<style>
.lf3vm6b4r {
  fill: currentColor;
  d: path("M4 22V2h16v20zm6.23-2.346h3.54v-.77h-3.54zM5 16.538h14V5.5H5z");
}

</style>
