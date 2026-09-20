<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9vz1cc6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tune-outline-sharp" /></template>
<style>
.c9vz1cc6h {
  fill: currentColor;
  d: path("M11.5 20.5v-5h1v2h8v1h-8v2zm-8-2v-1h5v1zm4-4v-2h-4v-1h4v-2h1v5zm4-2v-1h9v1zm4-4v-5h1v2h4v1h-4v2zm-12-2v-1h9v1z");
}

</style>
