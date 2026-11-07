<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dmnkhrp7z"/><path class="s6450lbyw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-off-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dmnkhrp7z {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m11.207 12.793l-4.228 4.228a16.9 16.9 0 0 1-3.643-5.404A16.8 16.8 0 0 1 2 5c0-.797.314-1.558.879-2.121A3 3 0 0 1 5 2h1c2.253 0 4.118 1.603 4.928 3.629c.351.877.592 1.812.592 2.761c0 .419-.05.84-.177 1.24a2.65 2.65 0 0 1-.636 1.077a1.123 1.123 0 0 0 0 1.586Zm2.421 1.822c.254-.027.485-.142.665-.322C15.252 13.335 16.683 13 18 13h1c.53 0 1.023.211 1.424.551C21.61 14.555 22 16.522 22 18v1c0 .797-.314 1.558-.879 2.121A3 3 0 0 1 19 22a16.8 16.8 0 0 1-6.617-1.336a17 17 0 0 1-3.097-1.707Z");
}

.s6450lbyw {
  d: path("m1.293 21.293l20-20a.999.999 0 1 1 1.414 1.414l-20 20a.999.999 0 1 1-1.414-1.414");
}

</style>
