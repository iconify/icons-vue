<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="alqc54g4m"/><circle class="po6vlitvx"/><path class="s6zu9-z9k"/><path class="jml7m8mfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-garage" /></template>
<style>
.alqc54g4m {
  cx: 15px;
  cy: 13px;
  r: 1px;
  fill: currentColor;
}

.jml7m8mfv {
  fill: currentColor;
  d: path("M20 2H4c-1.1 0-2 .9-2 2v16c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m-1 15.69c0 .45-.35.81-.78.81h-.44c-.44 0-.78-.36-.78-.81V16.5H7v1.19c0 .45-.35.81-.78.81h-.44c-.43 0-.78-.36-.78-.81v-6.5c.82-2.47 1.34-4.03 1.56-4.69c.05-.16.12-.29.19-.4c.02-.02.03-.04.05-.06c.38-.53.92-.54.92-.54h8.56s.54.01.92.53c.02.03.03.05.05.07c.07.11.14.24.19.4c.22.66.74 2.23 1.56 4.69z");
}

.po6vlitvx {
  cx: 9px;
  cy: 13px;
  r: 1px;
  fill: currentColor;
}

.s6zu9-z9k {
  fill: currentColor;
  d: path("m8.33 7.5l-.66 2h8.66l-.66-2z");
}

</style>
