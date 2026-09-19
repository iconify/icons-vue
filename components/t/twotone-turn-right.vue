<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uozeuqnbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-turn-right" /></template>
<style>
.uozeuqnbt {
  fill: currentColor;
  d: path("m17.17 11l-1.59 1.59L17 14l4-4l-4-4l-1.41 1.41L17.17 9H9c-1.1 0-2 .9-2 2v9h2v-9z");
}

</style>
