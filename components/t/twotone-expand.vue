<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwga7cb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-expand" /></template>
<style>
.wwga7cb-p {
  fill: currentColor;
  d: path("M4 20h16v2H4zM4 2h16v2H4zm9 7h3l-4-4l-4 4h3v6H8l4 4l4-4h-3z");
}

</style>
