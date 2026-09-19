<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cndqcs5ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-photo-library" /></template>
<style>
.cndqcs5ux {
  fill: currentColor;
  d: path("M20 4v12H8V4zm0-2H8c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m-8.5 9.67l1.69 2.26l2.48-3.1L19 15H9zM2 6v14c0 1.1.9 2 2 2h14v-2H4V6z");
}

</style>
