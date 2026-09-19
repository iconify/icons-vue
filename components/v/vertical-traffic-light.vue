<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="dshwbobrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:vertical-traffic-light" /></template>
<style>
.dshwbobrv {
  fill: currentColor;
  d: path("M32 2c-8.25 0-15 6.751-15 15v30c0 8.25 6.75 15 15 15s15-6.75 15-15V17c0-8.249-6.75-15-15-15m0 56.25a7.5 7.5 0 0 1-7.5-7.5a7.5 7.5 0 1 1 7.5 7.5m0-18.75a7.5 7.5 0 0 1-7.5-7.5a7.5 7.5 0 1 1 7.5 7.5m0-18.75a7.5 7.5 0 0 1-7.5-7.5a7.5 7.5 0 1 1 7.5 7.5");
}

</style>
