<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d74jcgbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-text-16-filled" /></template>
<style>
.d74jcgbxc {
  fill: currentColor;
  d: path("M1 5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2zm3.5 0a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1zM4 7.5a.5.5 0 0 0 .5.5h6a.5.5 0 0 0 0-1h-6a.5.5 0 0 0-.5.5M4.5 9a.5.5 0 0 0 0 1h4a.5.5 0 0 0 0-1z");
}

</style>
