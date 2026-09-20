<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="g74vjccbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:search-28-filled" /></template>
<style>
.g74vjccbl {
  fill: currentColor;
  d: path("M18.473 19.888A9.46 9.46 0 0 1 12.5 22a9.5 9.5 0 1 1 9.5-9.5a9.46 9.46 0 0 1-2.113 5.973l5.82 5.82a1 1 0 0 1-1.414 1.414zM20 12.5a7.5 7.5 0 1 0-15 0a7.5 7.5 0 0 0 15 0");
}

</style>
