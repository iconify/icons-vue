<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru4s_gs6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:phone-android-sharp" /></template>
<style>
.ru4s_gs6x {
  fill: currentColor;
  d: path("M10.23 19.654h3.54v-.77h-3.54zM6 22V2h12v20zm1-5.462h10V5.5H7z");
}

</style>
