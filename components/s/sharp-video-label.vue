<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kg-n76gtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-video-label" /></template>
<style>
.kg-n76gtw {
  fill: currentColor;
  d: path("M23 3H1v18h22zm-2 13H3V5h18z");
}

</style>
