<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7e1occkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-text-2-sharp" /></template>
<style>
.u7e1occkl {
  fill: currentColor;
  d: path("M8.385 11.596h7.307v-1H8.385zm1 2.885h5.307v-1H9.385zM6 22V2h12.077v4.83H19v3.686h-.923V22z");
}

</style>
