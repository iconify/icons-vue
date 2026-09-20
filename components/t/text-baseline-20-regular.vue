<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hf-my5weh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-baseline-20-regular" /></template>
<style>
.hf-my5weh {
  fill: currentColor;
  d: path("M10.461 3.806a.5.5 0 0 0-.921 0l-4 9.5a.5.5 0 1 0 .92.388L8.017 10h3.968l1.555 3.694a.5.5 0 1 0 .922-.388zM11.563 9H8.438L10 5.288zM2.5 16a.5.5 0 0 0 0 1h15a.5.5 0 0 0 0-1z");
}

</style>
