<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rss0egbho"/><path class="ohj1l5e-r"/><path class="y_5gu2b4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-view-comfy-alt" /></template>
<style>
.ohj1l5e-r {
  fill: currentColor;
  d: path("M7 7h4v4H7zm6 0h4v4h-4zm-6 6h4v4H7zm6 0h4v4h-4z");
}

.rss0egbho {
  fill: currentColor;
  d: path("M4 18h16V6H4zm9-11h4v4h-4zm0 6h4v4h-4zM7 7h4v4H7zm0 6h4v4H7z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.y_5gu2b4c {
  fill: currentColor;
  d: path("M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2m0 14H4V6h16z");
}

</style>
