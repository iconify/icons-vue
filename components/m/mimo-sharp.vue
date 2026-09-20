<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1iybfyae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mimo-sharp" /></template>
<style>
.w1iybfyae {
  fill: currentColor;
  d: path("M7.192 20v-1.538l.77-.77H3V4h18v13.692h-4.962l.77.77V20z");
}

</style>
