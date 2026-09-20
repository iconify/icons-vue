<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="m-7l8cc2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:red-triangle-pointed-up" /></template>
<style>
.m-7l8cc2z {
  fill: var(--svg-color--e75a70, #e75a70);
  d: path("M19.146 7.639c-.63-.901-1.637-.884-2.236.038L6.09 24.323C5.491 25.245 5.9 26 7 26h23c1.1 0 1.483-.737.854-1.639z");
}

</style>
