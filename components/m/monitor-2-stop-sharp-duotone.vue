<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pp09mi-yi"/><path class="piwe_wb9n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:monitor-2-stop-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.piwe_wb9n {
  d: path("M9 6L15 6C15.5523 6 16 6.4477 16 7L16 13C16 13.5523 15.5523 14 15 14L9 14C8.4477 14 8 13.5523 8 13L8 7C8 6.4477 8.4477 6 9 6Z");
}

.pp09mi-yi {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 18L2 18C1.4477 18 1 17.5523 1 17L1 3C1 2.4477 1.4477 2 2 2L22 2C22.5523 2 23 2.4477 23 3L23 17C23 17.5523 22.5523 18 22 18L13 18L13 20L17 20L17 22L7 22L7 20L11 20L11 18Z");
}

</style>
