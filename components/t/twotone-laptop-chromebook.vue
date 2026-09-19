<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="huhq7rrms"/><path class="rwzgto0ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-laptop-chromebook" /></template>
<style>
.huhq7rrms {
  fill: currentColor;
  d: path("M4 5h16v10H4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.rwzgto0ix {
  fill: currentColor;
  d: path("M22 18V3H2v15H0v2h24v-2zm-8 0h-4v-1h4zm6-3H4V5h16z");
}

</style>
