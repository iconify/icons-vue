<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9u-lu7se"/><path class="kyyvrqbfe"/><path class="z4bgkkb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-lyrics" /></template>
<style>
.kyyvrqbfe {
  fill: currentColor;
  d: path("M15 11.97V16H6l-2 2V4h11v2.03c.52-.69 1.2-1.25 2-1.6V4c0-1.1-.9-2-2-2H4c-1.1 0-1.99.9-1.99 2L2 22l4-4h9c1.1 0 2-.9 2-2v-2.42a5.16 5.16 0 0 1-2-1.61");
}

.s9u-lu7se {
  fill: currentColor;
  d: path("M6 6h7v2H6zm0 6h4v2H6z");
}

.z4bgkkb9y {
  fill: currentColor;
  d: path("M6 9h7v2H6zm14-2.82c-.31-.11-.65-.18-1-.18c-1.66 0-3 1.34-3 3s1.34 3 3 3s3-1.34 3-3V3h2V1h-4z");
}

</style>
