<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjjn0qblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tab-close-inactive-outline-sharp" /></template>
<style>
.mjjn0qblx {
  fill: currentColor;
  d: path("M14 22v-2h4v2zm-6 0v-2h4v2zM4 10H2V6h2zm0 6H2v-4h2zm2 6H2v-4h2v2h2zm5.9-8.5l2.1-2.1l2.1 2.1l1.4-1.4l-2.1-2.1l2.1-2.1l-1.4-1.4L14 8.6l-2.1-2.1l-1.4 1.4l2.1 2.1l-2.1 2.1zM6 18V2h16v16zm2-2h12V4H8zm0 0V4z");
}

</style>
