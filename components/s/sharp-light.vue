<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qio4mbnnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-light" /></template>
<style>
.qio4mbnnv {
  fill: currentColor;
  d: path("M13 6.06V3h-2v3.06A9.006 9.006 0 0 0 3.22 17H8c0 2.21 1.79 4 4 4s4-1.79 4-4h4.78A9.006 9.006 0 0 0 13 6.06M12 15H5c0-3.86 3.14-7 7-7s7 3.14 7 7z");
}

</style>
