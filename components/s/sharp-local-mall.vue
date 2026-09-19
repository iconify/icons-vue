<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcc73wbep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-local-mall" /></template>
<style>
.jcc73wbep {
  fill: currentColor;
  d: path("M21 6h-4c0-2.76-2.24-5-5-5S7 3.24 7 6H3v16h18zm-9-3c1.66 0 3 1.34 3 3H9c0-1.66 1.34-3 3-3m0 10c-2.76 0-5-2.24-5-5h2c0 1.66 1.34 3 3 3s3-1.34 3-3h2c0 2.76-2.24 5-5 5");
}

</style>
