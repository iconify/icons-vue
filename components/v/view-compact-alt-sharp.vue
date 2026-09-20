<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0lcqyb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-compact-alt-sharp" /></template>
<style>
.v0lcqyb-q {
  fill: currentColor;
  d: path("M7.5 16.5h4v-4h-4zm0-5h4v-4h-4zm5 5h4v-4h-4zm0-5h4v-4h-4zM2 20V4h20v16z");
}

</style>
