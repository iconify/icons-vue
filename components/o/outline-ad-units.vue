<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzk4-kbrd"/><path class="i4dnfxb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-ad-units" /></template>
<style>
.i4dnfxb_d {
  fill: currentColor;
  d: path("M16 7H8v2h8z");
}

.lzk4-kbrd {
  fill: currentColor;
  d: path("M17 1H7c-1.1 0-2 .9-2 2v18c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2V3c0-1.1-.9-2-2-2M7 4V3h10v1zm0 14V6h10v12zm0 3v-1h10v1z");
}

</style>
