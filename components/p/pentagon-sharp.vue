<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h48ovabea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pentagon-sharp" /></template>
<style>
.h48ovabea {
  fill: currentColor;
  d: path("M6.366 20.5L2.596 9.192L12 2.616l9.404 6.576l-3.77 11.308z");
}

</style>
