<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="fm--4d9cv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:text-h-four-light" /></template>
<style>
.fm--4d9cv {
  fill: currentColor;
  d: path("M150 56v120a6 6 0 0 1-12 0v-54H46v54a6 6 0 0 1-12 0V56a6 6 0 0 1 12 0v54h92V56a6 6 0 0 1 12 0m104 128a6 6 0 0 1-6 6h-10v18a6 6 0 0 1-12 0v-18h-50a6 6 0 0 1-4.74-9.68l56-72A6 6 0 0 1 238 112v66h10a6 6 0 0 1 6 6m-28-54.51L188.27 178H226Z");
}

</style>
