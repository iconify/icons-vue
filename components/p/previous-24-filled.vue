<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-j-ubbbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:previous-24-filled" /></template>
<style>
.d-j-ubbbb {
  fill: currentColor;
  d: path("M3 3.75a.75.75 0 0 1 1.5 0v16.5a.75.75 0 0 1-1.5 0zm18 1.003c0-1.408-1.578-2.24-2.74-1.444L7.763 10.503a1.75 1.75 0 0 0-.01 2.88l10.499 7.302c1.16.807 2.749-.024 2.749-1.437z");
}

</style>
