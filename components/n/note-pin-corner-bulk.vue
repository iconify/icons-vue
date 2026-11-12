<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="h3e06682f"/><path class="s2ox-ob3g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-pin-corner-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.h3e06682f {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 9H10a.997.997 0 0 0-1 1v10a1 1 0 0 1-1 1H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v2a1 1 0 0 1-1 1");
}

.s2ox-ob3g {
  d: path("M20 12a1 1 0 0 1 0 2v1.586l.707.707c.182.182.326.398.424.635c.286.69.163 1.561-.549 1.932c-.18.093-.379.141-.582.14h-2v2a1 1 0 0 1-2 0v-2h-2a1.25 1.25 0 0 1-.582-.14c-.712-.371-.835-1.242-.549-1.932c.098-.237.242-.453.424-.635l.707-.707V14a1 1 0 0 1 0-2Z");
}

</style>
