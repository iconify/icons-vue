<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3hhis53x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-done" /></template>
<style>
.l3hhis53x {
  fill: currentColor;
  d: path("M9 16.2L4.8 12l-1.4 1.4L9 19L21 7l-1.4-1.4z");
}

</style>
