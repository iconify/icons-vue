<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rnmdk1ncl"/><path class="shnylacfb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tablet-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rnmdk1ncl {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 7V17C23 19.2091 21.2091 21 19 21H5C2.79086 21 1 19.2091 1 17V7C1 4.79086 2.79086 3 5 3H19C21.2091 3 23 4.79086 23 7Z");
}

.shnylacfb {
  d: path("M13.5 8.5C13.5 9.3284 12.8284 10 12 10C11.1716 10 10.5 9.3284 10.5 8.5C10.5 7.6716 11.1716 7 12 7C12.8284 7 13.5 7.6716 13.5 8.5Z");
}

</style>
