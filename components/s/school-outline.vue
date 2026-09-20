<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjwz0dblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:school-outline" /></template>
<style>
.yjwz0dblc {
  fill: currentColor;
  d: path("m12 18.692l-6-3.261v-4.846L3.077 9L12 4.154L20.923 9v6.385h-1V9.562L18 10.585v4.846zm0-5.992L18.83 9L12 5.3L5.17 9zm0 4.852l5-2.7v-3.717l-5 2.708l-5-2.708v3.717zm0-3.487");
}

</style>
