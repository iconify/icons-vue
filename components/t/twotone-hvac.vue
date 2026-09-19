<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amh53_3dv"/><path class="bn6ebpb5p"/><path class="vt174qbyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-hvac" /></template>
<style>
.amh53_3dv {
  fill: currentColor;
  d: path("M5 19h14V5H5zm7-13c3.31 0 6 2.69 6 6s-2.69 6-6 6s-6-2.69-6-6s2.69-6 6-6");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.bn6ebpb5p {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H5V5h14z");
}

.vt174qbyc {
  fill: currentColor;
  d: path("M12 18c3.31 0 6-2.69 6-6s-2.69-6-6-6s-6 2.69-6 6s2.69 6 6 6m0-2c-1.01 0-1.91-.39-2.62-1h5.24c-.71.61-1.61 1-2.62 1m0-8c1.01 0 1.91.39 2.62 1H9.38c.71-.61 1.61-1 2.62-1m-3.44 2h6.89c.26.45.44.96.51 1.5h-7.9c.06-.54.23-1.05.5-1.5m7.39 2.5c-.07.54-.24 1.05-.51 1.5H8.56c-.26-.45-.44-.96-.51-1.5z");
}

</style>
