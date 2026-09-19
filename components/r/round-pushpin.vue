<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="uk4g79bsv"/><circle class="jybny6bov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:round-pushpin" /></template>
<style>
.jybny6bov {
  cx: 45px;
  cy: 19px;
  r: 17px;
  fill: var(--svg-color--ed4c5c, #ed4c5c);
}

.uk4g79bsv {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
  d: path("M42.6 29.4L2 62l32.6-40.6z");
}

</style>
