<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kh989uf3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:thumbnail-bar-sharp" /></template>
<style>
.kh989uf3m {
  fill: currentColor;
  d: path("M3 19V5h5v14zm6 0V5h12v14z");
}

</style>
