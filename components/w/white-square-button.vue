<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="r9scpwboa"/><path class="z7x0mu8oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:white-square-button" /></template>
<style>
.r9scpwboa {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
  d: path("M2 2h60v60H2z");
}

.z7x0mu8oe {
  fill: var(--svg-color--333, #333);
  d: path("M10 10h44v44H10z");
}

</style>
