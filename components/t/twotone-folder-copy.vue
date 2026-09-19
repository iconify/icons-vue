<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqhya8g2b"/><path class="ahj8dpgaj"/><path class="hwzwy1bba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-folder-copy" /></template>
<style>
.ahj8dpgaj {
  fill: currentColor;
  d: path("M21 4h-7l-2-2H7c-1.1 0-1.99.9-1.99 2L5 15c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2m0 11H7V4h4.17l2 2H21z");
}

.hwzwy1bba {
  fill: currentColor;
  d: path("M3 6H1v13c0 1.1.9 2 2 2h17v-2H3z");
}

.uqhya8g2b {
  fill: currentColor;
  d: path("M11.17 4H7v11h14V6h-7.83z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
