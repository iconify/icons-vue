<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_9-n3bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:south-east" /></template>
<style>
.q_9-n3bwy {
  fill: currentColor;
  d: path("M9 18v-1h7.292L5 5.708L5.708 5L17 16.292V9h1v9z");
}

</style>
