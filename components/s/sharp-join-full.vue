<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<ellipse class="z7mg04vth"/><path class="yfmet9bsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-join-full" /></template>
<style>
.yfmet9bsl {
  fill: currentColor;
  d: path("M7.5 12c0-.97.23-4.16 3.03-6.5C9.75 5.19 8.9 5 8 5c-3.86 0-7 3.14-7 7s3.14 7 7 7c.9 0 1.75-.19 2.53-.5c-2.8-2.34-3.03-5.53-3.03-6.5M16 5c-.9 0-1.75.19-2.53.5c2.8 2.34 3.03 5.53 3.03 6.5s-.23 4.16-3.03 6.5c.78.31 1.63.5 2.53.5c3.86 0 7-3.14 7-7s-3.14-7-7-7");
}

.z7mg04vth {
  cx: 12px;
  cy: 12px;
  fill: currentColor;
  rx: 3px;
  ry: 5.74px;
}

</style>
