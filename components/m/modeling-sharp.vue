<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xd2aaibmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:modeling-sharp" /></template>
<style>
.xd2aaibmh {
  fill: currentColor;
  d: path("m18 20.5l-4-4l4-4l1.4 1.4l-1.575 1.6H22v2h-4.175l1.575 1.6zM2 20v-7h10v7zm4-8.5l-1.4-1.4l1.575-1.6H2v-2h4.175L4.6 4.9L6 3.5l4 4zm6-.5V4h10v7z");
}

</style>
