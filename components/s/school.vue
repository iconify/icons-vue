<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8ghvfuls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:school" /></template>
<style>
.v8ghvfuls {
  fill: currentColor;
  d: path("M19.923 15.385V9.562L12 13.846L3.077 9L12 4.154L20.923 9v6.385zM12 18.692l-6-3.261v-4.077l6 3.262l6-3.262v4.077z");
}

</style>
