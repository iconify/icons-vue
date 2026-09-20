<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="bzr3b5blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-12-filled" /></template>
<style>
.bzr3b5blr {
  fill: currentColor;
  d: path("M2 2.75A.75.75 0 0 1 2.75 2h6a.75.75 0 0 1 .75.75v1.5a.75.75 0 0 1-1.5 0V3.5H6.5v5h.25a.75.75 0 0 1 0 1.5h-2a.75.75 0 0 1 0-1.5H5v-5H3.5v.75a.75.75 0 0 1-1.5 0z");
}

</style>
