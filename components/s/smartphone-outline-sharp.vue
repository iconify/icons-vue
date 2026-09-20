<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prnjn1bxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:smartphone-outline-sharp" /></template>
<style>
.prnjn1bxv {
  fill: currentColor;
  d: path("M5 23V1h14v22zm2-3v1h10v-1zm0-2h10V6H7zM7 4h10V3H7zm0 0V3zm0 16v1z");
}

</style>
