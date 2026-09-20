<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_oz0vb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tablet-android-outline-sharp" /></template>
<style>
.h_oz0vb7o {
  fill: currentColor;
  d: path("M4 22V2h16v20zm1-4.461V21h14v-3.462zm5.23 2.115h3.54v-.77h-3.54zM5 16.538h14V5.5H5zM5 4.5h14V3H5zm0 0V3zm0 13.039V21z");
}

</style>
