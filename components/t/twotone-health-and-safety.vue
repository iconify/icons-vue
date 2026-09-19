<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6i1c1r4b"/><path class="etm94sjoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-health-and-safety" /></template>
<style>
.etm94sjoe {
  fill: currentColor;
  d: path("M10.5 13H8v-3h2.5V7.5h3V10H16v3h-2.5v2.5h-3zM12 2L4 5v6.09c0 5.05 3.41 9.76 8 10.91c4.59-1.15 8-5.86 8-10.91V5zm6 9.09c0 4-2.55 7.7-6 8.83c-3.45-1.13-6-4.82-6-8.83v-4.7l6-2.25l6 2.25z");
}

.f6i1c1r4b {
  fill: currentColor;
  d: path("M12 4.14L6 6.39v4.7c0 4 2.55 7.7 6 8.83c3.45-1.13 6-4.82 6-8.83v-4.7zM16 13h-2.5v2.5h-3V13H8v-3h2.5V7.5h3V10H16z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
