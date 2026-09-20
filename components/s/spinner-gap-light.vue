<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kbmi2cb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:spinner-gap-light" /></template>
<style>
.kbmi2cb2l {
  fill: currentColor;
  d: path("M134 32v32a6 6 0 0 1-12 0V32a6 6 0 0 1 12 0m90 90h-32a6 6 0 0 0 0 12h32a6 6 0 0 0 0-12m-46.5 47a6 6 0 0 0-8.5 8.5l22.63 22.62a6 6 0 0 0 8.48-8.48ZM128 186a6 6 0 0 0-6 6v32a6 6 0 0 0 12 0v-32a6 6 0 0 0-6-6m-49.5-17l-22.62 22.64a6 6 0 1 0 8.48 8.48L87 177.5a6 6 0 1 0-8.5-8.5M70 128a6 6 0 0 0-6-6H32a6 6 0 0 0 0 12h32a6 6 0 0 0 6-6m-5.64-72.12a6 6 0 0 0-8.48 8.48L78.5 87a6 6 0 1 0 8.5-8.5Z");
}

</style>
