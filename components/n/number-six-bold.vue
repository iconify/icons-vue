<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="id47rsb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:number-six-bold" /></template>
<style>
.id47rsb9v {
  fill: currentColor;
  d: path("M128 100a59 59 0 0 0-7.81.53l26.27-46.64a12 12 0 0 0-20.92-11.78L76 130.13A60 60 0 1 0 128 100m0 96a36 36 0 1 1 36-36a36 36 0 0 1-36 36");
}

</style>
