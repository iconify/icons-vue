<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8zlilb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-insert-comment" /></template>
<style>
.w8zlilb7z {
  fill: currentColor;
  d: path("M20 4v13.17L18.83 16H4V4zm0-2H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h14l4 4V4c0-1.1-.9-2-2-2m-2 10H6v2h12zm0-3H6v2h12zm0-3H6v2h12z");
}

</style>
