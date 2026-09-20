<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="een9bablf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:title-outline" /></template>
<style>
.een9bablf {
  fill: currentColor;
  d: path("M11.385 19V6.25H6.019V5H18v1.25h-5.365V19z");
}

</style>
