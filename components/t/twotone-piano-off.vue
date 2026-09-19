<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wuf-3g3ts"/><path class="mbvrf4pms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-piano-off" /></template>
<style>
.mbvrf4pms {
  fill: currentColor;
  d: path("M21.19 21.19L2.81 2.81L1.39 4.22L3 5.83V19c0 1.1.9 2 2 2h13.17l1.61 1.61zM8.25 19H5V7.83l2 2v3.67c0 .55.45 1 1 1h.25zm1.5 0v-4.5H10c.46 0 .82-.31.94-.73l3.31 3.31V19zM11 8.17L5.83 3H19c1.1 0 2 .9 2 2v13.17l-2-2V5h-2v8.5c0 .19-.07.36-.16.51L13 10.17V5h-2z");
}

.wuf-3g3ts {
  fill: currentColor;
  d: path("M8.25 19H5V7.83l2 2v3.67c0 .55.45 1 1 1h.25zm1.5 0v-4.5H10c.46 0 .82-.31.94-.73l3.31 3.31V19zM13 10.17V5h-2v3.17zm6 6V5h-2v8.5c0 .19-.07.36-.16.51z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
