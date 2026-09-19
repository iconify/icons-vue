<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6cuozbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-signal-cellular-alt-1-bar" /></template>
<style>
.e6cuozbxd {
  fill: currentColor;
  d: path("M5 14h3v6H5z");
}

</style>
