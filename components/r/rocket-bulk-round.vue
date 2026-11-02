<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gyax4-b5o"/><path class="o8vh8nbwm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rocket-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gyax4-b5o {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 7h2.403c1.038-1.794 2.551-3.103 4.453-3.919C16.784 2.255 18.918 2 21 2a1 1 0 0 1 1 1c-.001 4.233-1.106 8.344-5 10.597V16c0 .637-.158 1.265-.48 1.816C15.617 19.364 13.706 20 12 20a1 1 0 0 1-1-1v-3.586L8.586 13H5a1 1 0 0 1-1-1c0-1.706.636-3.617 2.184-4.52A3.6 3.6 0 0 1 8 7M3 22a1 1 0 0 1-1-1c0-1.675.068-4.481 1.293-5.707a3.8 3.8 0 0 1 1.267-.841a3.827 3.827 0 0 1 4.147 6.255C7.481 21.932 4.675 22 3 22");
}

.o8vh8nbwm {
  d: path("m9.563 8.637l.543-1.084a1 1 0 1 1 1.788.894l-1.998 3.997l-.002.003a1 1 0 1 1-1.788-.894L9.55 8.664zm1.99 5.469l1.084-.543l.027-.014l.89-.444l1.999-.999a1 1 0 1 1 .894 1.788l-1.084.543l-.027.014l-.89.444l-1.999.999a1 1 0 1 1-.894-1.788M2 21c0-1.675.068-4.481 1.293-5.707a3.828 3.828 0 0 1 5.414 5.414C7.481 21.932 4.675 22 3 22a1 1 0 0 1-1-1m2.017-1.017q.682-.02 1.359-.1a7 7 0 0 0 1.255-.257c.222-.071.493-.164.662-.333a1.828 1.828 0 0 0-2.586-2.586c-.169.169-.262.44-.333.662a7 7 0 0 0-.257 1.255q-.08.677-.1 1.359");
}

</style>
