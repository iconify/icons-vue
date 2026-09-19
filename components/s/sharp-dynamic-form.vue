<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l29eg7ojy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-dynamic-form" /></template>
<style>
.l29eg7ojy {
  fill: currentColor;
  d: path("M17 20v-9h-2V4h7l-2 5h2zm-2-7v7H2v-7zm-8.75 2.75h-1.5v1.5h1.5zM13 4v7H2V4zM6.25 6.75h-1.5v1.5h1.5z");
}

</style>
