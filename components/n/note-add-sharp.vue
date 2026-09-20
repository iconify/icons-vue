<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="db7ekjori"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:note-add-sharp" /></template>
<style>
.db7ekjori {
  fill: currentColor;
  d: path("M11.5 17.5h1v-3h3v-1h-3v-3h-1v3h-3v1h3zM5 21V3h9.5L19 7.5V21zm9-13h4l-4-4z");
}

</style>
