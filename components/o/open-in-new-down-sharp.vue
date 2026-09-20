<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ty-lzqbvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:open-in-new-down-sharp" /></template>
<style>
.ty-lzqbvr {
  fill: currentColor;
  d: path("M4 20V4h16v7.616h-1V5H5v14h6.616v1zm10 0v-1h4.312L9.089 9.777l.688-.688L19 18.287V14h1v6z");
}

</style>
