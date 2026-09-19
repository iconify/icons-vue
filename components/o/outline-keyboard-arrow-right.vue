<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fk4hx468i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-keyboard-arrow-right" /></template>
<style>
.fk4hx468i {
  fill: currentColor;
  d: path("M8.59 16.59L13.17 12L8.59 7.41L10 6l6 6l-6 6z");
}

</style>
