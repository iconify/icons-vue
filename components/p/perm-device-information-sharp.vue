<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0nltgb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:perm-device-information-sharp" /></template>
<style>
.c0nltgb9x {
  fill: currentColor;
  d: path("M11.5 15.962v-5h1v5zm.5-6.808q-.261 0-.438-.177t-.177-.438t.177-.439t.438-.177t.439.177t.176.439t-.177.438t-.438.177M6 22V2h12v20zm1-3.5h10v-13H7z");
}

</style>
