<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ho1hiqbzp"/><path class="j2ocj64rv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-bag-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ho1hiqbzp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 5h14a1 1 0 0 1 1 1v15a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1");
}

.j2ocj64rv {
  d: path("M8 6a4 4 0 0 1 8 0a1 1 0 0 1-2 0a2 2 0 1 0-4 0a1 1 0 0 1-2 0");
}

</style>
