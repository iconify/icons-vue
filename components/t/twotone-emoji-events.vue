<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjdl1-wvj"/><path class="ejnycbb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-emoji-events" /></template>
<style>
.ejnycbb9z {
  fill: currentColor;
  d: path("M19 5h-2V3H7v2H5c-1.1 0-2 .9-2 2v1c0 2.55 1.92 4.63 4.39 4.94A5.01 5.01 0 0 0 11 15.9V19H7v2h10v-2h-4v-3.1a5.01 5.01 0 0 0 3.61-2.96C19.08 12.63 21 10.55 21 8V7c0-1.1-.9-2-2-2M5 8V7h2v3.82C5.84 10.4 5 9.3 5 8m7 6c-1.65 0-3-1.35-3-3V5h6v6c0 1.65-1.35 3-3 3m7-6c0 1.3-.84 2.4-2 2.82V7h2z");
}

.pjdl1-wvj {
  fill: currentColor;
  d: path("M12 14c-1.65 0-3-1.35-3-3V5h6v6c0 1.65-1.35 3-3 3");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
