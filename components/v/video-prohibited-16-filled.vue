<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vcti9obee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-prohibited-16-filled" /></template>
<style>
.vcti9obee {
  fill: currentColor;
  d: path("M4.5 6a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m-2.096 7.303a3.5 3.5 0 0 0 4.898-4.898zM8.5 3A2.5 2.5 0 0 1 11 5.5v5a2.5 2.5 0 0 1-1.5 2.29A5.5 5.5 0 0 0 2 5.6v-.1A2.5 2.5 0 0 1 4.5 3zm-4 4a3.5 3.5 0 0 0-2.803 5.596l4.899-4.899A3.5 3.5 0 0 0 4.5 7m9.535-2.776a1.25 1.25 0 0 1 1.961 1.028v5.498a1.25 1.25 0 0 1-1.96 1.028L11.9 10.304q.02-.14.02-.283v-4.04q0-.144-.02-.283z");
}

</style>
