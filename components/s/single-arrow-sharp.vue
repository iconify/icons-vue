<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1yj47bwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:single-arrow-sharp" /></template>
<style>
.m1yj47bwu {
  fill: currentColor;
  d: path("m9.698 18.5l4.654-6.5l-4.654-6.5h1.22L15.57 12l-4.654 6.5z");
}

</style>
