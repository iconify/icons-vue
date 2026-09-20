<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ldpgifbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-clip-48-filled" /></template>
<style>
.ldpgifbkh {
  fill: currentColor;
  d: path("M10.25 8A6.25 6.25 0 0 0 4 14.25v19.5A6.25 6.25 0 0 0 10.25 40h27.5A6.25 6.25 0 0 0 44 33.75v-19.5A6.25 6.25 0 0 0 37.75 8zM18 18a1.5 1.5 0 0 1 2.218-1.317l11 6a1.5 1.5 0 0 1 0 2.634l-11 6A1.5 1.5 0 0 1 18 30z");
}

</style>
