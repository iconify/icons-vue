<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxpus9swc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-landscape" /></template>
<style>
.dxpus9swc {
  fill: currentColor;
  d: path("M13.2 7.07L10.25 11l2.25 3c.33.44.24 1.07-.2 1.4a.994.994 0 0 1-1.4-.2c-1.05-1.4-2.31-3.07-3.1-4.14c-.4-.53-1.2-.53-1.6 0l-4 5.33c-.49.67-.02 1.61.8 1.61h18c.82 0 1.29-.94.8-1.6l-7-9.33a.993.993 0 0 0-1.6 0");
}

</style>
