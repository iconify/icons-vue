<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfu4pj2_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-short-24-regular" /></template>
<style>
.nfu4pj2_y {
  fill: currentColor;
  d: path("M16.75 2A3.25 3.25 0 0 1 20 5.25v13.5A3.25 3.25 0 0 1 16.75 22h-9.5A3.25 3.25 0 0 1 4 18.75V5.25A3.25 3.25 0 0 1 7.25 2zm-9.5 1.5A1.75 1.75 0 0 0 5.5 5.25v13.5c0 .966.784 1.75 1.75 1.75h9.5a1.75 1.75 0 0 0 1.75-1.75V5.25a1.75 1.75 0 0 0-1.75-1.75zM9 9.756c0-1.186 1.311-1.903 2.31-1.263l3.502 2.247a1.5 1.5 0 0 1 0 2.526l-3.502 2.247c-.998.64-2.31-.076-2.31-1.262z");
}

</style>
