<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8npfxbyr"/><path class="vwst72bli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-imagesearch-roller" /></template>
<style>
.vwst72bli {
  fill: currentColor;
  d: path("M20 7V3c0-.55-.45-1-1-1H7c-.55 0-1 .45-1 1v1H4c-1.1 0-2 .9-2 2v4c0 1.1.9 2 2 2h8v3h-1c-.55 0-1 .45-1 1v6c0 .55.45 1 1 1h4c.55 0 1-.45 1-1v-6c0-.55-.45-1-1-1h-1v-3c0-1.1-.9-2-2-2H4V6h2v1c0 .55.45 1 1 1h12c.55 0 1-.45 1-1M8 4h10v2H8zm6 17h-2v-4h2z");
}

.x8npfxbyr {
  fill: currentColor;
  d: path("M8 4h10v2H8zm4 13h2v4h-2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
