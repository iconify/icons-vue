<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_q9ossjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:small-24-filled" /></template>
<style>
.h_q9ossjz {
  fill: currentColor;
  d: path("M6.25 4.5A1.75 1.75 0 0 0 4.5 6.25v1.5a.75.75 0 0 1-1.5 0v-1.5A3.25 3.25 0 0 1 6.25 3h1.5a.75.75 0 0 1 0 1.5zM10.2 8a2.25 2.25 0 0 0-2.25 2.25v3.5A2.25 2.25 0 0 0 10.2 16h3.5a2.25 2.25 0 0 0 2.25-2.25v-3.5A2.25 2.25 0 0 0 13.7 8zm7.55-3.5c.966 0 1.75.784 1.75 1.75v1.5a.75.75 0 0 0 1.5 0v-1.5A3.25 3.25 0 0 0 17.75 3h-1.5a.75.75 0 0 0 0 1.5zm0 15a1.75 1.75 0 0 0 1.75-1.75v-1.5a.75.75 0 0 1 1.5 0v1.5A3.25 3.25 0 0 1 17.75 21h-1.5a.75.75 0 0 1 0-1.5zm-11.5 0a1.75 1.75 0 0 1-1.75-1.75v-1.5a.75.75 0 0 0-1.5 0v1.5A3.25 3.25 0 0 0 6.25 21h1.5a.75.75 0 0 0 0-1.5z");
}

</style>
