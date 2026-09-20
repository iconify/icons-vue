<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2aqjhbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:phone-multiple-24-filled" /></template>
<style>
.c2aqjhbmd {
  fill: currentColor;
  d: path("M8.25 2A2.25 2.25 0 0 0 6 4.25v13a2.25 2.25 0 0 0 2.25 2.25h5.5A2.25 2.25 0 0 0 16 17.25v-13A2.25 2.25 0 0 0 13.75 2zM9 16.25a.75.75 0 0 1 .75-.75h2.5a.75.75 0 0 1 0 1.5h-2.5a.75.75 0 0 1-.75-.75M10.75 22a2.25 2.25 0 0 1-2.122-1.5h5.622A2.75 2.75 0 0 0 17 17.75V4.628a2.25 2.25 0 0 1 1.5 2.122v11A4.25 4.25 0 0 1 14.25 22z");
}

</style>
