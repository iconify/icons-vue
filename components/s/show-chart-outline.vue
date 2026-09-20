<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="de0ysmkkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:show-chart-outline" /></template>
<style>
.de0ysmkkl {
  fill: currentColor;
  d: path("m3.5 17.808l-.73-.731l6.807-6.808l4 4l6.985-8l.707.67l-7.653 8.83l-4.039-4.038z");
}

</style>
