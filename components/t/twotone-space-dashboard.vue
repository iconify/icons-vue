<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hg-35sbze"/><path class="s5cxumhbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-space-dashboard" /></template>
<style>
.hg-35sbze {
  fill: currentColor;
  d: path("M5 19V5h6v14zm14 0h-6v-7h6zm0-9h-6V5h6z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.s5cxumhbh {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2M5 19V5h6v14zm14 0h-6v-7h6zm0-9h-6V5h6z");
}

</style>
