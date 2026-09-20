<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="mqc5ysb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:red-triangle-pointed-down" /></template>
<style>
.mqc5ysb8a {
  fill: var(--svg-color--e75a70, #e75a70);
  d: path("M19.146 26.361c-.63.901-1.637.884-2.236-.038L6.09 9.677C5.491 8.754 5.9 8 7 8h23c1.1 0 1.483.737.854 1.639z");
}

</style>
