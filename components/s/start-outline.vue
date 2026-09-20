<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gp4ljwb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:start-outline" /></template>
<style>
.gp4ljwb8m {
  fill: currentColor;
  d: path("M3 17.5v-11h1v11zm12.712-.212l-.714-.688l4.1-4.1H6.385v-1h12.694l-4.056-4.1l.689-.688L21 12z");
}

</style>
