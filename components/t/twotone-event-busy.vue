<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpeg5hafp"/><path class="tyiwsacse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-event-busy" /></template>
<style>
.qpeg5hafp {
  fill: currentColor;
  d: path("M5 5h14v2H5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.tyiwsacse {
  fill: currentColor;
  d: path("M19 3h-1V1h-2v2H8V1H6v2H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H5V9h14zm0-12H5V5h14zM9.29 17.47l2.44-2.44l2.44 2.44l1.06-1.06l-2.44-2.44l2.44-2.44l-1.06-1.06l-2.44 2.44l-2.44-2.44l-1.06 1.06l2.44 2.44l-2.44 2.44z");
}

</style>
