<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zub62lhld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-3-sharp" /></template>
<style>
.zub62lhld {
  fill: currentColor;
  d: path("M9.385 19.23h5.307v-1H9.385zM6 22V2h12.077v4.83H19v3.686h-.923V22z");
}

</style>
