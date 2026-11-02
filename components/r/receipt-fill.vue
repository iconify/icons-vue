<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yb1a8-b7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:receipt-fill" /></template>
<style>
.yb1a8-b7i {
  fill: currentColor;
  d: path("M6 2h12a3 3 0 0 1 3 3v15c.003.406-.193.788-.525 1.023c-.674.478-1.631.235-2.182-.316a.413.413 0 0 0-.586 0a2.4 2.4 0 0 1-1.707.707a2.4 2.4 0 0 1-1.707-.707a.413.413 0 0 0-.586 0a2.4 2.4 0 0 1-1.707.707a2.4 2.4 0 0 1-1.707-.707a.413.413 0 0 0-.586 0A2.4 2.4 0 0 1 8 21.414a2.4 2.4 0 0 1-1.707-.707a.413.413 0 0 0-.586 0a1.95 1.95 0 0 1-1.345.57C3.622 21.277 3 20.761 3 20V5a3 3 0 0 1 3-3m2 4a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2Zm0 4a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2Zm0 4a1 1 0 0 0 0 2h4a1 1 0 0 0 0-2Z");
}

</style>
