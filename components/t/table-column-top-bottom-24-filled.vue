<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="soh86dbkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-column-top-bottom-24-filled" /></template>
<style>
.soh86dbkd {
  fill: currentColor;
  d: path("M9.5 21h5v-1.5h-5zm6.5 0h1.75A3.25 3.25 0 0 0 21 17.75V16h-5zm5-6.5v-5h-5v5zM21 8V6.25A3.25 3.25 0 0 0 17.75 3H16v5zm-6.5-5h-5v1.5h5zM8 3H6.25A3.25 3.25 0 0 0 3 6.25V8h5zM3 9.5v5h5v-5zM3 16v1.75A3.25 3.25 0 0 0 6.25 21H8v-5zm11.5-6.5v5h-5v-5z");
}

</style>
