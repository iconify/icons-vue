<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qav6brbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:vertical-align-center" /></template>
<style>
.qav6brbvh {
  fill: currentColor;
  d: path("M8 19h3v4h2v-4h3l-4-4zm8-14h-3V1h-2v4H8l4 4zM4 11v2h16v-2z");
}

</style>
