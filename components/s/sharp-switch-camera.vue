<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xn3ogcbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-switch-camera" /></template>
<style>
.xn3ogcbqp {
  fill: currentColor;
  d: path("M22 4h-5.17L15 2H9L7.17 4H2v16h20zm-7 11.5V13H9v2.5L5.5 12L9 8.5V11h6V8.5l3.5 3.5z");
}

</style>
