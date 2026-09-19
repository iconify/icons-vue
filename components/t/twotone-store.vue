<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y84wcytgu"/><path class="r7a6mj8mu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-store" /></template>
<style>
.r7a6mj8mu {
  fill: currentColor;
  d: path("M4 4h16v2H4zm16 3H4l-1 5v2h1v6h10v-6h4v6h2v-6h1v-2zm-8 11H6v-4h6zm-6.96-6l.6-3h12.72l.6 3z");
}

.y84wcytgu {
  fill: currentColor;
  d: path("m5.64 9l-.6 3h13.92l-.6-3z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
