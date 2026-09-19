<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbt048bva"/><path class="si93ckb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-enhanced-encryption" /></template>
<style>
.dbt048bva {
  fill: currentColor;
  d: path("M6 20h12V10H6zm2-6h3v-3h2v3h3v2h-3v3h-2v-3H8z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.si93ckb5h {
  fill: currentColor;
  d: path("M18 8h-1V6c0-2.76-2.24-5-5-5S7 3.24 7 6v2H6c-1.1 0-2 .9-2 2v10c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V10c0-1.1-.9-2-2-2M8.9 6c0-1.71 1.39-3.1 3.1-3.1s3.1 1.39 3.1 3.1v2H8.9zM18 20H6V10h12zm-7-1h2v-3h3v-2h-3v-3h-2v3H8v2h3z");
}

</style>
