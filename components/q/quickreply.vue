<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gi7gjuq9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:quickreply" /></template>
<style>
.gi7gjuq9d {
  fill: currentColor;
  d: path("M19 23v-5h-2v-6h5l-1.7 4h2.2zM2 22V4q0-.825.588-1.412T4 2h16q.825 0 1.413.588T22 4v6h-7v8H6z");
}

</style>
