<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imhrn7p4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:monitor-heart-sharp" /></template>
<style>
.imhrn7p4k {
  fill: currentColor;
  d: path("M2 11V4h20v7h-5.375l-1.95-3.9h-1.35L10 13.75L8.625 11zm0 9v-7h5.375l1.95 3.9h1.35L14 10.25L15.375 13H22v7z");
}

</style>
