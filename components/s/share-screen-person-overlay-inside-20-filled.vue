<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rxc536b5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:share-screen-person-overlay-inside-20-filled" /></template>
<style>
.rxc536b5v {
  fill: currentColor;
  d: path("M2 7a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3zm3-1a1 1 0 0 0-1 1v3a1 1 0 0 0 1 1h3a1 1 0 0 0 1-1V7a1 1 0 0 0-1-1zm10 1.5a1.5 1.5 0 1 0-3 0a1.5 1.5 0 0 0 3 0M12 10a1 1 0 0 0-1 1v1a2 2 0 0 0 2 2h1a2 2 0 0 0 2-2v-1a1 1 0 0 0-1-1z");
}

</style>
