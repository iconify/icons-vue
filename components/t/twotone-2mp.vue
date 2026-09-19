<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fx4hy3zbg"/><path class="dqgvah66f"/><path class="d-1btyoxf"/><path class="bn6ebpb5p"/><path class="k5ks6njdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-2mp" /></template>
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

.fx4hy3zbg {
  fill: currentColor;
  d: path("M5 19h14V5H5zm13-5.5V16c0 .55-.45 1-1 1h-2v1.5h-1.5v-6H17c.55 0 1 .45 1 1M10 9c0-.55.45-1 1-1h2V7h-3V5.5h3.5c.55 0 1 .45 1 1V8c0 .55-.45 1-1 1h-2v1h3v1.5H10zm-4 4.5c0-.55.45-1 1-1h4.5c.55 0 1 .45 1 1v5H11V14h-1v3H8.5v-3h-1v4.5H6z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.k5ks6njdl {
  fill: currentColor;
  d: path("M14.5 10h-3V9h2c.55 0 1-.45 1-1V6.5c0-.55-.45-1-1-1H10V7h3v1h-2c-.55 0-1 .45-1 1v2.5h4.5z");
}

</style>
