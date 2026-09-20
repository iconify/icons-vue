<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uph2ylfok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:signal-wifi-bad-outline-sharp" /></template>
<style>
.uph2ylfok {
  fill: currentColor;
  d: path("M12 21L0 9q2.375-2.425 5.488-3.713T12 4t6.513 1.288T24 9l-3.7 3.7q-.425-.125-.875-.2t-.925-.075q-2.525 0-4.3 1.763T12.425 18.5q0 .475.075.925t.2.875zm4.4 1L15 20.6l2.1-2.1l-2.1-2.1l1.4-1.4l2.1 2.1l2.1-2.1l1.4 1.4l-2.075 2.1L22 20.6L20.6 22l-2.1-2.075z");
}

</style>
