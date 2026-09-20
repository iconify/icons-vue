<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4odjybkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tab-outline-sharp" /></template>
<style>
.m4odjybkx {
  fill: currentColor;
  d: path("M4 18h16v-8h-7V6H4zm-2 2V4h20v16zm2-2V6z");
}

</style>
