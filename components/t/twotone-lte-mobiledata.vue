<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsu1xmbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-lte-mobiledata" /></template>
<style>
.qsu1xmbgs {
  fill: currentColor;
  d: path("M6 14h3v2H4V8h2zm3-4h2v6h2v-6h2V8H9zm12 0V8h-5v8h5v-2h-3v-1h3v-2h-3v-1z");
}

</style>
