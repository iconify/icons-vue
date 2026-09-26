<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="setbkfbbg"/><path class="shnylacfb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tablet-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.setbkfbbg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 20C23 20.5523 22.5523 21 22 21L2 21C1.44772 21 1 20.5523 1 20L1 4C1 3.44772 1.44772 3 2 3L22 3C22.5523 3 23 3.44772 23 4L23 20Z");
}

.shnylacfb {
  d: path("M13.5 8.5C13.5 9.3284 12.8284 10 12 10C11.1716 10 10.5 9.3284 10.5 8.5C10.5 7.6716 11.1716 7 12 7C12.8284 7 13.5 7.6716 13.5 8.5Z");
}

</style>
