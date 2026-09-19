<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xy6qogb0c"/><path class="bn6ebpb5p"/><path class="pzpsoyeon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-24mp" /></template>
<style>
.bn6ebpb5p {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H5V5h14z");
}

.pzpsoyeon {
  fill: currentColor;
  d: path("M11 10H8V9h2c.55 0 1-.45 1-1V6.5c0-.55-.45-1-1-1H6.5V7h3v1h-2c-.55 0-1 .45-1 1v2.5H11zm5 1.5h1.5V10h1V8.5h-1v-3H16v3h-1.5v-3H13V10h3z");
}

.xy6qogb0c {
  fill: currentColor;
  d: path("M7.5 14h1v3H10v-3h1v4.5h1.5v-5c0-.55-.45-1-1-1H7c-.55 0-1 .45-1 1v5h1.5zm9.5-1.5h-3.5v6H15V17h2c.55 0 1-.45 1-1v-2.5c0-.55-.45-1-1-1m-.5 3H15V14h1.5z");
}

</style>
