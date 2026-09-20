<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9j5hbbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tablet-android-sharp" /></template>
<style>
.c9j5hbbqz {
  fill: currentColor;
  d: path("M3 23V1h18v22zm7-3h4v-1h-4zm-5-4h14V6H5z");
}

</style>
