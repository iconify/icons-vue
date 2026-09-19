<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjecepb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-turn-left" /></template>
<style>
.cjecepb2m {
  fill: currentColor;
  d: path("m6.83 11l1.59 1.59L7 14l-4-4l4-4l1.41 1.41L6.83 9H15c1.1 0 2 .9 2 2v9h-2v-9z");
}

</style>
