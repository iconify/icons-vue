<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqwcj0b4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:trending-down-outline" /></template>
<style>
.mqwcj0b4q {
  fill: currentColor;
  d: path("M16 17.096v-1h3.33l-6.026-5.938l-4 4L3 7.804l.708-.708l5.596 5.596l4-4L20 15.39v-3.293h1v5z");
}

</style>
