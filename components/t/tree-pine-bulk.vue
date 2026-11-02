<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uik9qgtxs"/><path class="ik13q-bgm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tree-pine-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ik13q-bgm {
  d: path("M13 18v3a1 1 0 0 1-2 0v-3a1 1 0 0 1 2 0");
}

.uik9qgtxs {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 8a1 1 0 0 1-.625-1.781l5-4a1 1 0 0 1 1.25 0l5 4A1.002 1.002 0 0 1 17 8h-.586l2.293 2.293c.182.182.326.398.424.635c.286.69.163 1.561-.549 1.932c-.18.093-.379.141-.582.14h-.586l3.293 3.293c.182.182.326.398.424.635c.286.69.163 1.561-.549 1.932c-.18.093-.379.141-.582.14H4a1.25 1.25 0 0 1-.582-.14c-.712-.371-.835-1.242-.549-1.932c.098-.237.242-.453.424-.635L6.586 13H6a1.25 1.25 0 0 1-.582-.14c-.712-.371-.835-1.242-.549-1.932c.098-.237.242-.453.424-.635L7.586 8Z");
}

</style>
