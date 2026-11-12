<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p05d90bur"/><path class="nlrwqmxju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-pin-corner-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nlrwqmxju {
  d: path("M14 12h6a1 1 0 0 1 0 2v1.586l.707.707c.182.182.326.398.424.635c.286.69.163 1.561-.549 1.932c-.18.093-.379.141-.582.14h-2v2a1 1 0 0 1-2 0v-2h-2a1.25 1.25 0 0 1-.582-.14c-.712-.371-.835-1.242-.549-1.932c.098-.237.242-.453.424-.635l.707-.707V14a1 1 0 0 1 0-2M2.55 18.275a7 7 0 0 1 1.5-2.225a7 7 0 0 1 2.225-1.5A6.9 6.9 0 0 1 9 14a1 1 0 0 1 0 2a4.97 4.97 0 0 0-3.536 1.464A4.97 4.97 0 0 0 4 21a1 1 0 0 1-2 0a6.9 6.9 0 0 1 .55-2.725");
}

.p05d90bur {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 7a5 5 0 1 1 10.001.001A5 5 0 0 1 4 7m6 8v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1c0-1.862.731-3.636 2.05-4.95a6.9 6.9 0 0 1 2.225-1.499A6.9 6.9 0 0 1 9 14a1 1 0 0 1 1 1");
}

</style>
