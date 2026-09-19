<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0qd-2izd"/><path class="bjhyr--qh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-looks-5" /></template>
<style>
.bjhyr--qh {
  fill: currentColor;
  d: path("M5 21h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2M5 5h14v14H5zm4 8h4v2H9v2h4a2 2 0 0 0 2-2v-2a2 2 0 0 0-2-2h-2V9h4V7H9z");
}

.z0qd-2izd {
  fill: currentColor;
  d: path("M19 5H5v14h14zm-4 4h-4v2h2a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2H9v-2h4v-2H9V7h6z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
