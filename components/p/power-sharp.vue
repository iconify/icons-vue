<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufn9jdg5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:power-sharp" /></template>
<style>
.ufn9jdg5n {
  fill: currentColor;
  d: path("M9.5 21v-3L6 14.5V7h2V3h2v4h4V3h2v4h2v7.5L14.5 18v3z");
}

</style>
