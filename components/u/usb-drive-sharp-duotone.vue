<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xt8_88b0a"/><path clip-rule="evenodd" class="wusl4fbeo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:usb-drive-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.wusl4fbeo {
  fill-rule: evenodd;
  d: path("M2 3L14 3C14.5523 3 15 3.4477 15 4L15 20C15 20.5523 14.5523 21 14 21L2 21C1.4477 21 1 20.5523 1 20L1 4C1 3.4477 1.4477 3 2 3ZM19 10C19 10.5523 18.5523 11 18 11C17.4477 11 17 10.5523 17 10C17 9.4477 17.4477 9 18 9C18.5523 9 19 9.4477 19 10ZM19 14C19 14.5523 18.5523 15 18 15C17.4477 15 17 14.5523 17 14C17 13.4477 17.4477 13 18 13C18.5523 13 19 13.4477 19 14Z");
}

.xt8_88b0a {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3L14 3C14.5523 3 15 3.4477 15 4L15 5L22 5C22.5523 5 23 5.4477 23 6L23 18C23 18.5523 22.5523 19 22 19L15 19L15 20C15 20.5523 14.5523 21 14 21L2 21C1.4477 21 1 20.5523 1 20L1 4C1 3.4477 1.4477 3 2 3Z");
}

</style>
