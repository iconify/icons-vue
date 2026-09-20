<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="im1ut2bsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:school-outline" /></template>
<style>
.im1ut2bsb {
  fill: currentColor;
  d: path("m12 21l-7-3.8v-6L1 9l11-6l11 6v8h-2v-6.9l-2 1.1v6zm0-8.3L18.85 9L12 5.3L5.15 9zm0 6.025l5-2.7V12.25L12 15l-5-2.75v3.775zm0-3.775");
}

</style>
