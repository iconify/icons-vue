<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="kwhch0b3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rename-a-28-regular" /></template>
<style>
.kwhch0b3a {
  fill: currentColor;
  d: path("M20.25 2a.75.75 0 0 1 0 1.5h-1.752v21h1.752a.75.75 0 0 1 0 1.5h-5a.75.75 0 0 1 0-1.5h1.748v-21H15.25a.75.75 0 0 1 0-1.5zm-4.252 4.5H5.754a2.25 2.25 0 0 0-2.25 2.25v10.5a2.25 2.25 0 0 0 2.25 2.25h10.244V23H5.754a3.75 3.75 0 0 1-3.75-3.75V8.75A3.75 3.75 0 0 1 5.754 5h10.244zM22.251 5a3.75 3.75 0 0 1 3.75 3.75v10.5a3.75 3.75 0 0 1-3.75 3.75h-2.753v-1.5h2.753a2.25 2.25 0 0 0 2.25-2.25V8.75a2.25 2.25 0 0 0-2.25-2.25h-2.753V5zM10 8a.75.75 0 0 1 .678.43l4.25 9a.75.75 0 1 1-1.356.64l-1.214-2.57H7.642l-1.214 2.57a.75.75 0 1 1-1.356-.64l4.25-9l.053-.094A.75.75 0 0 1 10 8m-1.65 6h3.3L10 10.505z");
}

</style>
