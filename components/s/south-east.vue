<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbnn7qwwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:south-east" /></template>
<style>
.vbnn7qwwz {
  fill: currentColor;
  d: path("M9 19v-2h6.6L4 5.4L5.4 4L17 15.6V9h2v10z");
}

</style>
