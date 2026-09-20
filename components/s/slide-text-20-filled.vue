<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vsow1y-rh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-text-20-filled" /></template>
<style>
.vsow1y-rh {
  fill: currentColor;
  d: path("M2 6.5A2.5 2.5 0 0 1 4.5 4h11A2.5 2.5 0 0 1 18 6.5v7a2.5 2.5 0 0 1-2.5 2.5h-11A2.5 2.5 0 0 1 2 13.5zm3.5.5a.5.5 0 0 0 0 1h4a.5.5 0 0 0 0-1zM5 10a.5.5 0 0 0 .5.5h7a.5.5 0 0 0 0-1h-7a.5.5 0 0 0-.5.5m.5 2a.5.5 0 0 0 0 1h5a.5.5 0 0 0 0-1z");
}

</style>
