<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xy7gytb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-collapse-24-regular" /></template>
<style>
.xy7gytb5w {
  fill: currentColor;
  d: path("M21.25 18a.75.75 0 0 1 0 1.5H5.75a.75.75 0 0 1 0-1.5zM6.5 7a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m-2 4a.5.5 0 0 0 0 1h4a.5.5 0 0 0 0-1zm16.75 2a.75.75 0 0 1 0 1.5h-7.5a.75.75 0 0 1 0-1.5zm0-5a.75.75 0 0 1 0 1.5h-7.5a.75.75 0 0 1 0-1.5zm0-5a.75.75 0 0 1 0 1.5H5.75a.75.75 0 0 1 0-1.5z");
}

</style>
