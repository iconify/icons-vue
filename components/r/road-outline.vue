<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bw3rlgxxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:road-outline" /></template>
<style>
.bw3rlgxxt {
  fill: currentColor;
  d: path("M5 19V5h1v14zm6.5 0v-3.077h1V19zm6.5 0V5h1v14zm-6.5-5.462v-3.076h1v3.077zm0-5.461V5h1v3.077z");
}

</style>
