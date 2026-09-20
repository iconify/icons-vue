<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itk4jibwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:select-window-outline-sharp" /></template>
<style>
.itk4jibwr {
  fill: currentColor;
  d: path("M2 22V9h4V2h16v13h-4v7zm2-2h12v-7H4zm14-7h2V6H8v3h10z");
}

</style>
