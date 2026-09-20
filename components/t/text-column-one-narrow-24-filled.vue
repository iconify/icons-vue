<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcascibmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-column-one-narrow-24-filled" /></template>
<style>
.pcascibmi {
  fill: currentColor;
  d: path("M9 5a1 1 0 0 0 0 2h6a1 1 0 1 0 0-2zm0 4a1 1 0 0 0 0 2h6a1 1 0 1 0 0-2zm-1 5a1 1 0 0 1 1-1h6a1 1 0 1 1 0 2H9a1 1 0 0 1-1-1m1 3a1 1 0 1 0 0 2h6a1 1 0 1 0 0-2z");
}

</style>
