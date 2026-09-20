<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-pz2uzsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:piano-sharp" /></template>
<style>
.z-pz2uzsh {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-1h3.654v-4.808h-1.25V5H5zm10.346 0H19V5h-2.404v9.192h-1.25zM9.54 19h4.923v-4.808h-1.25V5H10.79v9.192H9.54z");
}

</style>
