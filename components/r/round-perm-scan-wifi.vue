<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nuoa_wb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-perm-scan-wifi" /></template>
<style>
.nuoa_wb9w {
  fill: currentColor;
  d: path("M12 3C7.41 3 3.86 4.53.89 6.59c-.49.33-.59 1-.22 1.46l9.78 12.04c.8.98 2.3.99 3.1 0l9.78-12.02a1 1 0 0 0-.22-1.46C20.14 4.54 16.59 3 12 3m0 13c-.55 0-1-.45-1-1v-4c0-.55.45-1 1-1s1 .45 1 1v4c0 .55-.45 1-1 1m-1-8V6h2v2z");
}

</style>
