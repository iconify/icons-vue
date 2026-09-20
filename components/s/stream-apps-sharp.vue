<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z05vgab-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stream-apps-sharp" /></template>
<style>
.z05vgab-j {
  fill: currentColor;
  d: path("M14.116 16.173v-7.48h7.653v6h-6.173zM6 22V2h12v4.923h-1V5.5H7v13h10v-1.423h1V22z");
}

</style>
