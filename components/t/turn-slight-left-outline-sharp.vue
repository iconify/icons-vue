<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kklm6bb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:turn-slight-left-outline-sharp" /></template>
<style>
.kklm6bb6k {
  fill: currentColor;
  d: path("M13.5 19.77v-7.312l-5.788-5.77V9.67h-1V5h4.669v1H8.4l6.1 6.08v7.69z");
}

</style>
