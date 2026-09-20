<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nf3jo9bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:star-half-outline" /></template>
<style>
.nf3jo9bly {
  fill: currentColor;
  d: path("m15.15 16.85l-.825-3.6l2.775-2.4l-3.65-.325l-1.45-3.4v7.8zm-7.825 2.073l1.24-5.313l-4.123-3.571l5.431-.472L12 4.557l2.127 5.01l5.43.472l-4.123 3.57l1.241 5.314L12 16.102z");
}

</style>
