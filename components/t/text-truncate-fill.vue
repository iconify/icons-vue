<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfq6j8nae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-truncate-fill" /></template>
<style>
.gfq6j8nae {
  fill: currentColor;
  d: path("M3 5h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m0 12h6a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m10 0h.01a1 1 0 0 1 0 2H13a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2m4 2h-.01a1 1 0 0 1 0-2H21a1 1 0 0 1 0 2");
}

</style>
