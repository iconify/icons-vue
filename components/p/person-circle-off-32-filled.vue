<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nvd0_0c4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-circle-off-32-filled" /></template>
<style>
.nvd0_0c4r {
  fill: currentColor;
  d: path("M2.293 2.293a1 1 0 0 1 1.414 0l26 26a1 1 0 1 1-1.414 1.414l-3.127-3.127A13.94 13.94 0 0 1 16 30C8.268 30 2 23.732 2 16c0-3.506 1.288-6.712 3.418-9.168L2.293 3.707a1 1 0 0 1 0-1.414M11.429 16A2.43 2.43 0 0 0 9 18.429c0 3.643 3.134 6.071 7 6.071c2.062 0 3.912-.695 5.192-1.894L14.586 16zM16 2c7.732 0 14 6.268 14 14c0 2.962-.921 5.708-2.491 7.97l-4.586-4.584q.076-.464.077-.957A2.43 2.43 0 0 0 20.571 16h-1.033l-1.885-1.885A3.749 3.749 0 0 0 16 7a3.75 3.75 0 0 0-3.366 2.096L8.027 4.49A13.94 13.94 0 0 1 16 2");
}

</style>
