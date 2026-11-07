<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtahr_cms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plug-off-fill-round" /></template>
<style>
.wtahr_cms {
  fill: currentColor;
  d: path("m20.707 2.707l-18 18a.999.999 0 1 1-1.414-1.414l4.176-4.176A5 5 0 0 1 5 13v-2c0-1.99 1.175-3.79 3-4.584V3a1 1 0 0 1 2 0v3h4V3a1 1 0 0 1 2 0v1.586l3.293-3.293a.999.999 0 1 1 1.414 1.414M8.478 17.764l9.625-9.624A5 5 0 0 1 19 11v2a5 5 0 0 1-5 5h-1v3a1 1 0 0 1-2 0v-3h-1a5 5 0 0 1-1.522-.236");
}

</style>
