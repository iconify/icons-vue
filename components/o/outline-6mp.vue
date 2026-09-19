<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-1btyoxf"/><path class="bn6ebpb5p"/><path class="jtlw3yzql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-6mp" /></template>
<style>
.bn6ebpb5p {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H5V5h14z");
}

.d-1btyoxf {
  fill: currentColor;
  d: path("M7.5 14h1v3H10v-3h1v4.5h1.5v-5c0-.55-.45-1-1-1H7c-.55 0-1 .45-1 1v5h1.5zm6 4.5H15V17h2c.55 0 1-.45 1-1v-2.5c0-.55-.45-1-1-1h-3.5zM15 14h1.5v1.5H15z");
}

.jtlw3yzql {
  fill: currentColor;
  d: path("M11 11.5h2.5c.55 0 1-.45 1-1V9c0-.55-.45-1-1-1h-2V7h3V5.5H11c-.55 0-1 .45-1 1v4c0 .55.45 1 1 1m.5-2.5H13v1.5h-1.5z");
}

</style>
