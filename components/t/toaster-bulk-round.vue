<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="djfohilqu"/><path class="vo-nfl9jh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:toaster-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.djfohilqu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 11a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

.vo-nfl9jh {
  d: path("M8 2c1.657.001 3 1.343 2.999 3v4a1 1 0 0 1-2 0V4.998a1 1 0 0 0-.317-.728a.96.96 0 0 0-.731-.269h-.003A.984.984 0 0 0 7 5v4a1 1 0 0 1-2 0V4.999A3 3 0 0 1 8 2m11 3v4a1 1 0 0 1-2 0V5a1 1 0 0 0-2 0v4a1 1 0 0 1-2 0V4.999A3 3 0 0 1 19 5m-1 12a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0Z");
}

</style>
