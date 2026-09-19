<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fh1o-tbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-turn-left" /></template>
<style>
.fh1o-tbgy {
  fill: currentColor;
  d: path("m6.83 11l1.58 1.59L7 14l-4-4l4-4l1.41 1.41L6.83 9H17v11h-2v-9z");
}

</style>
