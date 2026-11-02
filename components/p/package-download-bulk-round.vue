<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ozzv6mtrh"/><path class="fjzmle77m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-download-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fjzmle77m {
  d: path("M4 7h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2m4.293 8.707a.999.999 0 1 1 1.414-1.414L11 15.586V12a1 1 0 0 1 2 0v3.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0Z");
}

.ozzv6mtrh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m3.106 7.553l1-2C4.848 4.069 6.307 3 8 3h8c1.693 0 3.152 1.069 3.894 2.553l1 2c.07.139.106.292.106.447v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 21H8a5 5 0 0 1-5-5V8c0-.155.036-.308.106-.447");
}

</style>
