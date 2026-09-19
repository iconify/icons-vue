<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da_7bo6mw"/><path class="jbzus25sp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-view-agenda" /></template>
<style>
.da_7bo6mw {
  fill: currentColor;
  d: path("M5 5h14v4H5zm0 10h14v4H5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.jbzus25sp {
  fill: currentColor;
  d: path("M19 13H5c-1.1 0-2 .9-2 2v4c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2v-4c0-1.1-.9-2-2-2m0 6H5v-4h14zm0-16H5c-1.1 0-2 .9-2 2v4c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 6H5V5h14z");
}

</style>
