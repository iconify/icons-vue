<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adabar7iv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-indent-decrease-24-regular" /></template>
<style>
.adabar7iv {
  fill: currentColor;
  d: path("M17.75 16a.75.75 0 0 1 0 1.5h-9a.75.75 0 0 1 0-1.5zM2.72 11.22l2-2a.75.75 0 0 1 1.133.976l-.073.084l-1.47 1.47l1.47 1.47a.75.75 0 0 1-.976 1.133l-.084-.073l-2-2a.75.75 0 0 1-.073-.976zl2-2zM20.75 11a.75.75 0 0 1 0 1.5h-12a.75.75 0 0 1 0-1.5zm-3-5a.75.75 0 0 1 0 1.5h-9a.75.75 0 0 1 0-1.5z");
}

</style>
