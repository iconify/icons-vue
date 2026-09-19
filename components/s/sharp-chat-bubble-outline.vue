<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dv-82bbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-chat-bubble-outline" /></template>
<style>
.dv-82bbeb {
  fill: currentColor;
  d: path("M22 2H2v20l4-4h16zm-2 14H6l-2 2V4h16z");
}

</style>
