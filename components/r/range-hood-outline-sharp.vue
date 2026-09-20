<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekimmoull"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:range-hood-outline-sharp" /></template>
<style>
.ekimmoull {
  fill: currentColor;
  d: path("M2 20v-7l5-5V3h10v5l5 5v7zm3.8-8h12.4L15 8.8V5H9v3.8zM4 18h16v-4H4zm6-1.3v-1.5h4v1.5z");
}

</style>
