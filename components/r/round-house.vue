<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="br397h5wb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-house" /></template>
<style>
.br397h5wb {
  fill: currentColor;
  d: path("M19 9.3V5c0-.55-.45-1-1-1h-1c-.55 0-1 .45-1 1v1.6l-3.33-3c-.38-.34-.96-.34-1.34 0l-8.36 7.53c-.34.3-.13.87.33.87H5v7c0 .55.45 1 1 1h3c.55 0 1-.45 1-1v-5h4v5c0 .55.45 1 1 1h3c.55 0 1-.45 1-1v-7h1.7c.46 0 .68-.57.33-.87zm-9 .7c0-1.1.9-2 2-2s2 .9 2 2z");
}

</style>
