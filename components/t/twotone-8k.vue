<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwy97pb4p"/><path class="xv0t_ubyt"/><path class="fzzx5ac3q"/><path class="bn6ebpb5p"/><path class="lvlyzzbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-8k" /></template>
<style>
.bn6ebpb5p {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H5V5h14z");
}

.fwy97pb4p {
  fill: currentColor;
  d: path("M8 10h1.5v1.5H8zm0 2.5h1.5V14H8z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.fzzx5ac3q {
  fill: currentColor;
  d: path("M7.5 15H10c.55 0 1-.45 1-1v-4c0-.55-.45-1-1-1H7.5c-.55 0-1 .45-1 1v4c0 .55.45 1 1 1m.5-5h1.5v1.5H8zm0 2.5h1.5V14H8z");
}

.lvlyzzbmm {
  fill: currentColor;
  d: path("M14.5 12.75L16.25 15H18l-2.25-3L18 9h-1.75l-1.75 2.25V9H13v6h1.5z");
}

.xv0t_ubyt {
  fill: currentColor;
  d: path("M5 19h14V5H5zm8-10h1.5v2.25L16.25 9H18l-2.25 3L18 15h-1.75l-1.75-2.25V15H13zm-6.5 1c0-.55.45-1 1-1H10c.55 0 1 .45 1 1v4c0 .55-.45 1-1 1H7.5c-.55 0-1-.45-1-1z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
