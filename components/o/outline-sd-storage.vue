<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndqc9cboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-sd-storage" /></template>
<style>
.ndqc9cboe {
  fill: currentColor;
  d: path("M18 4v16H6V8.83L10.83 4zm0-2h-8L4 8v12c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2M9 7h2v4H9zm3 0h2v4h-2zm3 0h2v4h-2z");
}

</style>
