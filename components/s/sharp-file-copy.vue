<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cst0x0bcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-file-copy" /></template>
<style>
.cst0x0bcx {
  fill: currentColor;
  d: path("M16 1H2v16h2V3h12zm-1 4l6 6v12H6V5zm-1 7h5.5L14 6.5z");
}

</style>
