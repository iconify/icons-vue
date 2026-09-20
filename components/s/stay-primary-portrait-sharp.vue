<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szjxkbytq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stay-primary-portrait-sharp" /></template>
<style>
.szjxkbytq {
  fill: currentColor;
  d: path("M12 16.462q-.261 0-.438-.177t-.177-.439t.177-.438t.438-.177t.439.177t.176.438t-.177.439t-.438.177m-.5-2.962V7.423h1V13.5zM6 22V2h12v20zm1-3.5h10v-13H7z");
}

</style>
