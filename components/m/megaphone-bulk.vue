<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sy6hjbi3e"/><path class="hpqdgnb0d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:megaphone-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hpqdgnb0d {
  d: path("M4 9.999V12a1 1 0 0 0 .999 1H11a1 1 0 0 1 0 2h-1v4a3 3 0 0 1-6 0v-4.171a3 3 0 0 1-2-2.827V10a3.004 3.004 0 0 1 2.999-3H11a1 1 0 0 1 0 2H5a1 1 0 0 0-1 .999M6 15v4a1 1 0 0 0 2 0v-4Z");
}

.sy6hjbi3e {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m10.553 7.106l8-4c.356-.181.75-.274 1.149-.273C20.924 2.836 22 3.735 22 5v12c0 1.265-1.076 2.164-2.298 2.167a2.5 2.5 0 0 1-1.149-.273l-8-4A1 1 0 0 1 10 14V8c0-.379.214-.725.553-.894");
}

</style>
