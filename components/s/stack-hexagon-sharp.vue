<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6mab2bek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stack-hexagon-sharp" /></template>
<style>
.z6mab2bek {
  fill: currentColor;
  d: path("m14.5 13.5l3.5-2v-4l-3.5-2l-3.5 2v4zM3.7 22.125L1.85 7.2L5 6.85V19h13.3l.125 1.325zM7 17V2h15v15z");
}

</style>
