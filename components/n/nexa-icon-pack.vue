<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h0pmrlbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nexa-icon-pack" /></template>
<style>
.h0pmrlbve {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.25 23A8.75 8.75 0 1 1 23 14.25V19c0 2.216-1.784 4-4 4zM25 14.25A8.75 8.75 0 1 1 33.75 23H29c-2.216 0-4-1.784-4-4zM33.75 25A8.75 8.75 0 1 1 25 33.75V29c0-2.216 1.784-4 4-4zM23 33.75A8.75 8.75 0 1 1 14.25 25H19c2.216 0 4 1.784 4 4z");
}

</style>
