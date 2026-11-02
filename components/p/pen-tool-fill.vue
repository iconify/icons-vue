<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jklmx4b7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pen-tool-fill" /></template>
<style>
.jklmx4b7i {
  fill: currentColor;
  d: path("M14.287 6.042a1 1 0 0 1 .607.511l2.928 5.855l1.885 1.885a2.414 2.414 0 0 1 0 3.414l-2 2a2.414 2.414 0 0 1-3.414 0l-1.885-1.885l-5.855-2.928a1 1 0 0 1-.511-.607l-3-10a1 1 0 0 1 1.245-1.245ZM6.121 7.535l1.172 1.172a.999.999 0 1 0 1.414-1.414L7.535 6.121a.999.999 0 1 0-1.414 1.414M11.01 10H11a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M17 14.414L14.414 17l1.293 1.293a.414.414 0 0 0 .586 0l2-2a.414.414 0 0 0 0-.586Z");
}

</style>
