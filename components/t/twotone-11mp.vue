<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5n43wtxv"/><path class="dqgvah66f"/><path class="d-1btyoxf"/><path class="bn6ebpb5p"/><path class="skxw93vaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-11mp" /></template>
<style>
.bn6ebpb5p {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H5V5h14z");
}

.d-1btyoxf {
  fill: currentColor;
  d: path("M7.5 14h1v3H10v-3h1v4.5h1.5v-5c0-.55-.45-1-1-1H7c-.55 0-1 .45-1 1v5h1.5zm6 4.5H15V17h2c.55 0 1-.45 1-1v-2.5c0-.55-.45-1-1-1h-3.5zM15 14h1.5v1.5H15z");
}

.dqgvah66f {
  fill: currentColor;
  d: path("M15 14h1.5v1.5H15z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.skxw93vaf {
  fill: currentColor;
  d: path("M9.5 11.5H11v-6H8V7h1.5zm5 0H16v-6h-3V7h1.5z");
}

.u5n43wtxv {
  fill: currentColor;
  d: path("M5 19h14V5H5zm13-5.5V16c0 .55-.45 1-1 1h-2v1.5h-1.5v-6H17c.55 0 1 .45 1 1m-5-8h3v6h-1.5V7H13zm-5 0h3v6H9.5V7H8zm-2 8c0-.55.45-1 1-1h4.5c.55 0 1 .45 1 1v5H11V14h-1v3H8.5v-3h-1v4.5H6z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
