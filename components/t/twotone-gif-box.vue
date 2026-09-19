<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b70o_vbpr"/><path class="gr6b09_5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-gif-box" /></template>
<style>
.b70o_vbpr {
  fill: currentColor;
  d: path("M5 5v14h14V5zm4.5 8v-1h1v1c0 .55-.45 1-1 1h-1c-.55 0-1-.45-1-1v-2c0-.55.45-1 1-1h1c.55 0 1 .45 1 1h-2v2zm3 1h-1v-4h1zm4-3h-2v.5H16v1h-1.5V14h-1v-4h3z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.gr6b09_5g {
  fill: currentColor;
  d: path("M19 19H5V5h14zM5 3c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zm6.5 11h1v-4h-1zm2 0h1v-1.5H16v-1h-1.5V11h2v-1h-3zm-4-2v1h-1v-2h2c0-.55-.45-1-1-1h-1c-.55 0-1 .45-1 1v2c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-1z");
}

</style>
