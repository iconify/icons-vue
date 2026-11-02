<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gfs3uib7x"/><path class="cbwi8-2-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:owl-bulk-round" /></template>
<style>
.cbwi8-2-o {
  d: path("M5 10a3 3 0 1 1 0 .003Zm8.236-1.168a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338M9 10a1 1 0 1 0-2 0a1 1 0 0 0 2 0m8 0a1 1 0 1 0-2 0a1 1 0 0 0 2 0m-4 3v2a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0M3 20h6v-2a1 1 0 0 1 2 0v2h2v-2a1 1 0 0 1 2 0v2h6a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2");
}

.cuyn6tgcc {
  fill: currentColor;
}

.gfs3uib7x {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4.514 2.143a12.4 12.4 0 0 0 3.53 1.447C9.337 3.897 10.674 4 12 4s2.663-.103 3.956-.41a12.4 12.4 0 0 0 3.53-1.447a1 1 0 0 1 1.442.486c.483 1.205.799 2.47.941 3.761C22.002 7.588 22 8.796 22 10c-.001 2.503-1.097 4.786-2.962 6.436c-3.868 3.42-10.208 3.42-14.076 0a8.8 8.8 0 0 1-2.163-2.861A8.3 8.3 0 0 1 2 10c0-1.204-.002-2.412.131-3.61c.142-1.291.458-2.556.941-3.761a1 1 0 0 1 1.442-.486");
}

</style>
