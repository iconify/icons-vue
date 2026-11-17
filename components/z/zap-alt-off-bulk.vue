<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gy_c9oq4l"/><path class="scc1kvjkf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-alt-off-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gy_c9oq4l {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15.328 14.086L7.471 6.228l1.351-3.04A2 2 0 0 1 10.65 2H16a1.582 1.582 0 0 1 1.372 2.364L14.723 9H17a1.416 1.416 0 0 1 1 2.414ZM12.5 15.5l.707.707L8.414 21a1.292 1.292 0 0 1-2.173-1.193L7.753 13H7a1.65 1.65 0 0 1-1.508-2.32l.673-1.515Z");
}

.scc1kvjkf {
  d: path("m2.707 4.293l17 17a.999.999 0 1 1-1.414 1.414l-17-17a.999.999 0 1 1 1.414-1.414");
}

</style>
