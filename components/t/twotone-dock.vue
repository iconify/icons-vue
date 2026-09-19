<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nm7lbubhr"/><path class="pahn6ybed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-dock" /></template>
<style>
.nm7lbubhr {
  fill: currentColor;
  d: path("M8 5h8v10H8z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.pahn6ybed {
  fill: currentColor;
  d: path("M8 21h8v2H8zm8-19.99L8 1c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2V3c0-1.1-.9-1.99-2-1.99M16 15H8V5h8z");
}

</style>
