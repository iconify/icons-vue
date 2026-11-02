<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nwx5rmbhu"/><path class="jdy9hqpvl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sword-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jdy9hqpvl {
  d: path("m5.707 11.293l7 7a.999.999 0 1 1-1.414 1.414L8.5 16.914L5.414 20l.293.293a.999.999 0 1 1-1.414 1.414l-2-2a1 1 0 0 1 1.414-1.414l.293.293L7.086 15.5l-1.567-1.567l-.001-.001l-1.225-1.225a.999.999 0 1 1 1.414-1.414");
}

.nwx5rmbhu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m6.293 13.293l11-11A1 1 0 0 1 18 2h3a1 1 0 0 1 1 1v3c0 .265-.105.52-.293.707l-11 11a1 1 0 0 1-1.414 0l-3-3a.997.997 0 0 1 0-1.414");
}

</style>
