<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="x74nr18ud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rename-28-regular" /></template>
<style>
.x74nr18ud {
  fill: currentColor;
  d: path("M16.251 2a.75.75 0 0 1 0 1.5h-1.499v21h1.499a.75.75 0 0 1 0 1.5h-4.497a.75.75 0 0 1 0-1.5h1.498v-21h-1.498a.75.75 0 0 1 0-1.5zm-3.999 4.5H5.754a2.25 2.25 0 0 0-2.25 2.25v10.5a2.25 2.25 0 0 0 2.25 2.25h6.498V23H5.754a3.75 3.75 0 0 1-3.75-3.75V8.75A3.75 3.75 0 0 1 5.754 5h6.498zM22.251 5a3.75 3.75 0 0 1 3.75 3.75v10.5a3.75 3.75 0 0 1-3.75 3.75h-6.499v-1.5h6.499a2.25 2.25 0 0 0 2.25-2.25V8.75a2.25 2.25 0 0 0-2.25-2.25h-6.499V5z");
}

</style>
