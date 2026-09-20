<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kg7ktw5_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tablet-48-regular" /></template>
<style>
.kg7ktw5_i {
  fill: currentColor;
  d: path("M20 31a1.25 1.25 0 1 0 0 2.5h8a1.25 1.25 0 1 0 0-2.5zM8.25 8A4.25 4.25 0 0 0 4 12.25v23.5A4.25 4.25 0 0 0 8.25 40h31.5A4.25 4.25 0 0 0 44 35.75v-23.5A4.25 4.25 0 0 0 39.75 8zM6.5 12.25c0-.966.784-1.75 1.75-1.75h31.5c.967 0 1.75.784 1.75 1.75v23.5a1.75 1.75 0 0 1-1.75 1.75H8.25a1.75 1.75 0 0 1-1.75-1.75z");
}

</style>
