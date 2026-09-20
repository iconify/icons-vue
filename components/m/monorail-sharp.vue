<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6x_oubjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:monorail-sharp" /></template>
<style>
.t6x_oubjd {
  fill: currentColor;
  d: path("M11 17h2v3h5v2H6v-2h5zM8 2h8q1.65 0 2.825 1.175T20 6v9.5q0 1.475-1.025 2.488T16.5 19H14v-3h-4v3H7.5q-1.475 0-2.488-1.012T4 15.5V6q0-1.65 1.163-2.825T8 2M6 7v3h12V7z");
}

</style>
