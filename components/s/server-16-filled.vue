<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bp-59m9cb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:server-16-filled" /></template>
<style>
.bp-59m9cb {
  fill: currentColor;
  d: path("M11.414 1.586A2 2 0 0 0 10 1H6a2 2 0 0 0-2 2v10a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2V3a2 2 0 0 0-.586-1.414M9.853 12.854a.5.5 0 0 1-.354.146h-3a.5.5 0 1 1 0-1h3a.5.5 0 0 1 .354.854m0-2a.5.5 0 0 1-.354.146h-3a.5.5 0 1 1 0-1h3a.5.5 0 0 1 .354.854m0-6A.5.5 0 0 1 9.499 5h-3a.5.5 0 0 1-.5-.5a.5.5 0 0 1 .5-.5h3a.5.5 0 0 1 .354.854");
}

</style>
