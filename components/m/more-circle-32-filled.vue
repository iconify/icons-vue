<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d9gjf4b0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:more-circle-32-filled" /></template>
<style>
.d9gjf4b0z {
  fill: currentColor;
  d: path("M16 30c7.732 0 14-6.268 14-14S23.732 2 16 2S2 8.268 2 16s6.268 14 14 14m-6-12a2 2 0 1 1 0-4a2 2 0 0 1 0 4m8-2a2 2 0 1 1-4 0a2 2 0 0 1 4 0m4 2a2 2 0 1 1 0-4a2 2 0 0 1 0 4");
}

</style>
