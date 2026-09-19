<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f57gb6bny"/><path class="i744c0dwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-sip" /></template>
<style>
.f57gb6bny {
  fill: currentColor;
  d: path("M15.5 10.5h2v1h-2z");
}

.i744c0dwj {
  fill: currentColor;
  d: path("M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2m-10 6.5H6.5v.75H10V15H5v-1.5h3.5v-.75H5V9h5zm3 4.5h-2V9h2zm6-6v4h-3.5v2H14V9z");
}

</style>
