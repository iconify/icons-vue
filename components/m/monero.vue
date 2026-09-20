<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="hcit2k8sl"/><path class="zy7rhbblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:monero" /></template>
<style>
.hcit2k8sl {
  fill: var(--svg-color--f60, #f60);
  d: path("M127.998 0C57.318 0 0 57.317 0 127.999c0 14.127 2.29 27.716 6.518 40.43H44.8V60.734l83.2 83.2l83.198-83.2v107.694h38.282c4.231-12.714 6.521-26.303 6.521-40.43C256 57.316 198.681 0 127.998 0");
}

.zy7rhbblt {
  fill: var(--svg-color--4c4c4c, #4c4c4c);
  d: path("m108.867 163.062l-36.31-36.311v67.765H18.623c22.47 36.863 63.051 61.48 109.373 61.48s86.907-24.617 109.374-61.48h-53.933V126.75l-36.31 36.31l-19.13 19.129l-19.128-19.128z");
}

</style>
