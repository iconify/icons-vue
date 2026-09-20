<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":308};
const content = `<path class="e31pl0bbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:replit-icon" /></template>
<style>
.e31pl0bbc {
  fill: var(--svg-color--f26207, #f26207);
  d: path("M0 19.2C0 8.596 8.596 0 19.2 0h89.6C119.404 0 128 8.596 128 19.2v83.2H19.2C8.596 102.4 0 93.804 0 83.2zm128 83.2h108.8c10.604 0 19.2 8.596 19.2 19.2v64c0 10.604-8.596 19.2-19.2 19.2H128zM0 224c0-10.604 8.596-19.2 19.2-19.2H128V288c0 10.604-8.596 19.2-19.2 19.2H19.2C8.596 307.2 0 298.604 0 288z");
}

</style>
