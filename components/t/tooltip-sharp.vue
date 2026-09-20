<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yey0pshjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tooltip-sharp" /></template>
<style>
.yey0pshjj {
  fill: currentColor;
  d: path("m12 22l-2.675-4H2V2h20v16h-7.325z");
}

</style>
