<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cj90qebuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sound-wave-circle-48-regular" /></template>
<style>
.cj90qebuc {
  fill: currentColor;
  d: path("M24 6.5C14.335 6.5 6.5 14.335 6.5 24S14.335 41.5 24 41.5S41.5 33.665 41.5 24S33.665 6.5 24 6.5M4 24C4 12.954 12.954 4 24 4s20 8.954 20 20s-8.954 20-20 20S4 35.046 4 24m16.75-8c.69 0 1.25.56 1.25 1.25v13.5a1.25 1.25 0 1 1-2.5 0v-13.5c0-.69.56-1.25 1.25-1.25M34 17.25a1.25 1.25 0 1 0-2.5 0v13.5a1.25 1.25 0 1 0 2.5 0zM14.75 20c.69 0 1.25.56 1.25 1.25v5.5a1.25 1.25 0 1 1-2.5 0v-5.5c0-.69.56-1.25 1.25-1.25m13.25.25a1.25 1.25 0 1 0-2.5 0v7.5a1.25 1.25 0 1 0 2.5 0z");
}

</style>
