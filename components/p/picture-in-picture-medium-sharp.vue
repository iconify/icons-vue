<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzf58kbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:picture-in-picture-medium-sharp" /></template>
<style>
.fzf58kbwi {
  fill: currentColor;
  d: path("M8 16V8h10v8zm-6 4v-2h18V4h2v16z");
}

</style>
