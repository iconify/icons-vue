<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iivqedcba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:responsive-layout-outline-sharp" /></template>
<style>
.iivqedcba {
  fill: currentColor;
  d: path("M4 20V9h5V4h11v16zm11-1h4V5h-9v4h5zm-5 0h4v-9h-4zm-5 0h4v-9H5zM15 9v1zm0 0");
}

</style>
