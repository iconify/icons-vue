<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j79hrstgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:panel-left-text-16-filled" /></template>
<style>
.j79hrstgz {
  fill: currentColor;
  d: path("M2 5.5A2.5 2.5 0 0 1 4.5 3h7A2.5 2.5 0 0 1 14 5.5v5a2.5 2.5 0 0 1-2.5 2.5h-7A2.5 2.5 0 0 1 2 10.5zm9.5 6.5a1.5 1.5 0 0 0 1.5-1.5v-5A1.5 1.5 0 0 0 11.5 4H8v8zm-7-7a.5.5 0 0 0 0 1h1a.5.5 0 0 0 0-1zM4 8a.5.5 0 0 0 .5.5h1a.5.5 0 0 0 0-1h-1A.5.5 0 0 0 4 8m.5 2a.5.5 0 0 0 0 1h1a.5.5 0 0 0 0-1z");
}

</style>
