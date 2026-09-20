<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kb6uxzbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pause-circle-32-filled" /></template>
<style>
.kb6uxzbmi {
  fill: currentColor;
  d: path("M16 30c7.732 0 14-6.268 14-14S23.732 2 16 2S2 8.268 2 16s6.268 14 14 14m-3-19.5a1 1 0 0 1 1 1v9a1 1 0 1 1-2 0v-9a1 1 0 0 1 1-1m5 1a1 1 0 1 1 2 0v9a1 1 0 1 1-2 0z");
}

</style>
