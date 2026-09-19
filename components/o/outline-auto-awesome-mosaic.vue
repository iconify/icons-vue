<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxbounb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-auto-awesome-mosaic" /></template>
<style>
.nxbounb5a {
  fill: currentColor;
  d: path("M3 5v14a2 2 0 0 0 2 2h6V3H5a2 2 0 0 0-2 2m6 14H5V5h4zM19 3h-6v8h8V5c0-1.1-.9-2-2-2m0 6h-4V5h4zm-6 12h6c1.1 0 2-.9 2-2v-6h-8zm2-6h4v4h-4z");
}

</style>
