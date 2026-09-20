<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skts64d7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stylus-highlighter-sharp" /></template>
<style>
.skts64d7v {
  fill: currentColor;
  d: path("M7 16V3h2.475L17 6.725V16zm-3 5l1-3h14l1 3z");
}

</style>
