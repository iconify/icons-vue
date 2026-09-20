<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rixwjegdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:padding-sharp" /></template>
<style>
.rixwjegdm {
  fill: currentColor;
  d: path("M7.346 8.885h1.539V7.346H7.346zm3.885 0h1.538V7.346h-1.538zm3.885 0h1.538V7.346h-1.538zM4 20V4h16v16z");
}

</style>
