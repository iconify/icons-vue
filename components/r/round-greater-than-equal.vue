<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="foubbfm0i"/><path class="pywi5nbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-greater-than-equal" /></template>
<style>
.foubbfm0i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m7.25 15l7.5-5l-7.5-5a.901.901 0 1 1 1-1.5l8.502 5.668a1 1 0 0 1 0 1.664L8.25 16.5a.901.901 0 1 1-1-1.5");
}

.pywi5nbeq {
  fill: currentColor;
  d: path("M17 20.998H7a1 1 0 0 1 0-2h10a1 1 0 0 1 0 2");
}

</style>
