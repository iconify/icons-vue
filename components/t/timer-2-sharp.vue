<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6uifebpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:timer-2-sharp" /></template>
<style>
.a6uifebpi {
  fill: currentColor;
  d: path("M8.5 18.116v-6.731h6.77v-4.27H8.5v-1.23h8v6.73H9.73v4.27h6.77v1.23z");
}

</style>
