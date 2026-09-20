<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kib19kboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:open-in-full-sharp" /></template>
<style>
.kib19kboj {
  fill: currentColor;
  d: path("M4 20v-7h1v5.312L18.312 5H13V4h7v7h-1V5.689L5.689 19H11v1z");
}

</style>
