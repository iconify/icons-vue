<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<ellipse class="z7mg04vth"/><path class="fu0ttfo5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-join-inner" /></template>
<style>
.fu0ttfo5h {
  fill: currentColor;
  d: path("M9.04 16.87c-.33.08-.68.13-1.04.13c-2.76 0-5-2.24-5-5s2.24-5 5-5c.36 0 .71.05 1.04.13c.39-.56.88-1.12 1.49-1.63C9.75 5.19 8.9 5 8 5c-3.86 0-7 3.14-7 7s3.14 7 7 7c.9 0 1.75-.19 2.53-.5c-.61-.51-1.1-1.07-1.49-1.63M16 5c-.9 0-1.75.19-2.53.5c.61.51 1.1 1.07 1.49 1.63c.33-.08.68-.13 1.04-.13c2.76 0 5 2.24 5 5s-2.24 5-5 5c-.36 0-.71-.05-1.04-.13c-.39.56-.88 1.12-1.49 1.63c.78.31 1.63.5 2.53.5c3.86 0 7-3.14 7-7s-3.14-7-7-7");
}

.z7mg04vth {
  cx: 12px;
  cy: 12px;
  fill: currentColor;
  rx: 3px;
  ry: 5.74px;
}

</style>
