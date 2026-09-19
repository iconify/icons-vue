<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7rvm8xuf"/><path class="y4gsmjbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-bookmark-add" /></template>
<style>
.k7rvm8xuf {
  fill: currentColor;
  d: path("M17 17.97V10.9A5 5 0 0 1 13 6c0-.34.03-.68.1-1H7v12.97l5-2.14z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.y4gsmjbvb {
  fill: currentColor;
  d: path("M21 7h-2v2h-2V7h-2V5h2V3h2v2h2zm-4 10.97l-5-2.14l-5 2.14V5h6.1c.15-.74.46-1.42.9-2H7c-1.1 0-2 .9-2 2v16l7-3l7 3V10.9c-.32.07-.66.1-1 .1s-.68-.03-1-.1z");
}

</style>
