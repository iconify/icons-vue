<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="aktlt3ojg"/><path class="scc1kvjkf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-off-bulk-round" /></template>
<style>
.aktlt3ojg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16.828 15.586L8.414 7.172l3.879-3.879c.31-.311.752-.456 1.186-.382C14.428 3.072 15 4.102 15 5v4a.997.997 0 0 0 1 1h2c.898 0 1.928.572 2.089 1.521a1.34 1.34 0 0 1-.382 1.186Zm-2.121 2.121l-3 3a1.36 1.36 0 0 1-1.186.382C9.572 20.928 9 19.898 9 19v-4a.997.997 0 0 0-1-1H6c-.898 0-1.928-.572-2.089-1.521a1.34 1.34 0 0 1 .382-1.186l2-2Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.scc1kvjkf {
  d: path("m2.707 4.293l17 17a.999.999 0 1 1-1.414 1.414l-17-17a.999.999 0 1 1 1.414-1.414");
}

</style>
