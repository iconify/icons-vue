<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n_boxvbbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mooneva-cycle" /></template>
<style>
.n_boxvbbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44 28.707c-3.187 4.32-8.313 7.122-14.093 7.122c-9.666 0-17.502-7.836-17.502-17.502c0-5.967 2.985-11.236 7.544-14.396C10.821 5.918 4 14.042 4 23.766C4 34.98 13.09 44.07 24.304 44.07c9.512 0 17.494-6.531 19.697-15.362");
}

</style>
