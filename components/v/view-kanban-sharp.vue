<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mc8y1cu8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-kanban-sharp" /></template>
<style>
.mc8y1cu8t {
  fill: currentColor;
  d: path("M7.5 16.5h1v-9h-1zm4-5h1v-4h-1zm4 3h1v-7h-1zM4 20V4h16v16z");
}

</style>
