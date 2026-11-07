<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vx-misbcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mails-fill-round" /></template>
<style>
.vx-misbcv {
  fill: currentColor;
  d: path("M9 2h8a5 5 0 0 1 5 5v8a1 1 0 0 1-2 0V7a3 3 0 0 0-3-3H9a1 1 0 0 0-1 1a1 1 0 0 1-2 0a3 3 0 0 1 3-3M3.677 9.263A4.98 4.98 0 0 1 7 8h6c1.228 0 2.406.445 3.323 1.263l-4.03 4.03c-.948.948-3.638.948-4.586 0Zm2.616 5.444C7.252 15.665 8.683 16 10 16s2.748-.335 3.707-1.293l3.824-3.824c.31.664.47 1.384.469 2.117v4a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5v-4c0-.733.158-1.453.469-2.117Z");
}

</style>
