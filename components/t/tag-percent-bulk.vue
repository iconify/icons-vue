<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mcs0p0bzj"/><path class="p2vn8gb6a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tag-percent-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mcs0p0bzj {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 7v13a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V7c0-.265.105-.52.293-.707l4-4A1 1 0 0 1 9 2h6c.265 0 .52.105.707.293l4 4A1 1 0 0 1 20 7");
}

.p2vn8gb6a {
  d: path("M11 5h2a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2m-4 7a2 2 0 1 1 3.999-.001A2 2 0 0 1 7 12m8.707.707l-6 6a.999.999 0 1 1-1.414-1.414l6-6a.999.999 0 1 1 1.414 1.414M13 18a2 2 0 1 1 3.999-.001A2 2 0 0 1 13 18");
}

</style>
