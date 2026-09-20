<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="xqtzudbty"/><path clip-rule="evenodd" class="ypp97vbjd"/><path class="vh7t-d01o"/><path clip-rule="evenodd" class="uhftw22-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:rewind" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.uhftw22-o {
  fill-rule: evenodd;
  d: path("M5.736 10L8 7.574v4.852zm-2.1.682a1 1 0 0 1 0-1.364L8.27 4.355c.619-.665 1.73-.226 1.73.682v9.926c0 .908-1.112 1.346-1.731.682z");
}

.vh7t-d01o {
  d: path("M3.637 9.318a1 1 0 0 0 0 1.364l4.632 4.963c.62.664 1.731.226 1.731-.682V5.037c0-.908-1.112-1.346-1.731-.682z");
}

.xqtzudbty {
  d: path("M8.637 9.318a1 1 0 0 0 0 1.364l4.632 4.963c.62.664 1.731.226 1.731-.682V5.037c0-.908-1.112-1.346-1.731-.682z");
}

.ypp97vbjd {
  fill-rule: evenodd;
  d: path("M10.736 10L13 7.574v4.852zm-2.1.682a1 1 0 0 1 0-1.364l4.633-4.963c.62-.664 1.731-.226 1.731.682v9.926c0 .908-1.112 1.346-1.731.682z");
}

</style>
