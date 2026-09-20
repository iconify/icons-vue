<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj9obk32d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speed-1-5-outline-sharp" /></template>
<style>
.jj9obk32d {
  fill: currentColor;
  d: path("M7.73 16.5v-8h-2v-1h3v9zm2.77 0v-1h1v1zm2.77 0v-1h4v-3h-4v-5h5v1h-4v3h4v5z");
}

</style>
