<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rep20fq8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-web-stories" /></template>
<style>
.rep20fq8t {
  fill: currentColor;
  d: path("M17 4h2v16h-2zM2 2v20h13V2zm19 16h1.5V6H21z");
}

</style>
