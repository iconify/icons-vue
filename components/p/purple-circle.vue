<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="j6bk8wgmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:purple-circle" /></template>
<style>
.j6bk8wgmi {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--aa8ed6, #aa8ed6);
}

</style>
