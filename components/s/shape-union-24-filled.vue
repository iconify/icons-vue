<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h43gg9u5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:shape-union-24-filled" /></template>
<style>
.h43gg9u5b {
  fill: currentColor;
  d: path("M5.25 2A3.25 3.25 0 0 0 2 5.25v8a3.25 3.25 0 0 0 3.25 3.25H7.5v2.25A3.25 3.25 0 0 0 10.75 22h8A3.25 3.25 0 0 0 22 18.75v-8a3.25 3.25 0 0 0-3.25-3.25H16.5V5.25A3.25 3.25 0 0 0 13.25 2z");
}

</style>
