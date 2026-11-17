<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xq6kprbhq"/><path class="vqyt9zbhv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:robot-vacuum-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.vqyt9zbhv {
  d: path("M7.106 14.447a5.472 5.472 0 1 1 9.788 0a.995.995 0 0 1-1.341.447a1 1 0 0 1-.447-1.341a3.474 3.474 0 0 0-4.658-4.659a3.47 3.47 0 0 0-1.554 4.659a1 1 0 1 1-1.788.894M12 15h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

.xq6kprbhq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.106 7.553C5.562 2.64 11.535.648 16.448 3.105c4.912 2.456 6.904 8.43 4.447 13.343c-2.456 4.912-8.43 6.904-13.343 4.447C2.64 18.439.649 12.465 3.106 7.553");
}

</style>
