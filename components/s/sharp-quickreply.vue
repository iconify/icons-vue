<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdbp_p5yp"/><path class="im-o75nsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-quickreply" /></template>
<style>
.fdbp_p5yp {
  fill: currentColor;
  d: path("M22 2H2v20l4-4h9v-8h7z");
}

.im-o75nsy {
  fill: currentColor;
  d: path("M22.5 16h-2.2l1.7-4h-5v6h2v5z");
}

</style>
