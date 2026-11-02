<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fym9dvbck"/><path class="mv5m2elnr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pig-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.fym9dvbck {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3.818 7.816c-.503-1.222-.744-2.534-.801-3.851A22 22 0 0 1 3 3a1 1 0 0 1 1-1c1.126 0 2.236.264 3.269.706a8.3 8.3 0 0 1 2.043 1.227c.889-.127 1.791-.158 2.688-.158s1.799.031 2.688.158a8.3 8.3 0 0 1 2.043-1.227C17.764 2.264 18.874 2 20 2a1 1 0 0 1 1 1q.002.483-.017.965c-.057 1.317-.298 2.629-.801 3.851C21.622 9.575 22 11.783 22 14a9.5 9.5 0 0 1-.499 3.105C20.515 19.982 18.108 21.999 15 22H9c-3.108-.001-5.515-2.018-6.501-4.895A9.6 9.6 0 0 1 2 14c0-2.217.378-4.425 1.818-6.184M10 13a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm4 0a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Z");
}

.mv5m2elnr {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 8C4 6 4 4 4 3c2 0 4 1 5 2c1.5-.3 4.5-.3 6 0c1-1 3-2 5-2c0 1 0 3-1 5c1.5 1.5 2 3.5 2 6c0 4-2.5 7-6 7H9c-3.5 0-6-3-6-7c0-2.5.5-4.5 2-6m4 0h.01M15 8h.01M12 11c2.76 0 5 1.34 5 3s-2.24 3-5 3s-5-1.34-5-3s2.24-3 5-3m-2 3h.01M14 14h.01");
}

</style>
