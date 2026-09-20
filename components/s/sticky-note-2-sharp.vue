<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cb3_dubzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sticky-note-2-sharp" /></template>
<style>
.cb3_dubzl {
  fill: currentColor;
  d: path("M19 14h-5v5zM4 20V4h16v10.289L14.288 20zm3.885-6.539H12v-1H7.885zm0-3.961h8.23v-1h-8.23z");
}

</style>
