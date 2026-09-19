<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfu7eobjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-airline-stops" /></template>
<style>
.gfu7eobjd {
  fill: currentColor;
  d: path("M19 8.7c-2.46 1.5-5.5 4.17-6 8.3h2v2H9v-2h2c-.5-4.5-4.37-8-9-8V7c4.39 0 8.22 2.55 10 6.3c1.38-2.97 3.86-5.03 5.96-6.31L14 7V5h7v7h-2z");
}

</style>
