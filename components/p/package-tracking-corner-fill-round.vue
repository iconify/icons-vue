<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xof-mzq6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-tracking-corner-fill-round" /></template>
<style>
.xof-mzq6w {
  fill: currentColor;
  d: path("M4.106 5.553C4.848 4.069 6.307 3 8 3h8c1.693 0 3.152 1.069 3.894 2.553l1 2A1 1 0 0 1 20 9H5v7a3 3 0 0 0 3 3a1 1 0 0 1 0 2a5 5 0 0 1-3.536-1.464A4.98 4.98 0 0 1 3 16V8c0-.155.036-.308.106-.447Zm10.707 14.658a33 33 0 0 1-1.322-1.435C12.878 18.061 12 16.985 12 16a5 5 0 0 1 10 0c0 .985-.878 2.061-1.491 2.776q-.64.737-1.322 1.435c-.488.504-.984 1-1.48 1.496a1 1 0 0 1-1.414 0c-.496-.496-.992-.992-1.48-1.496M16 16a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
