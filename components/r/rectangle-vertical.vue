<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hu9wd0b4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:rectangle-vertical" /></template>
<style>
.hu9wd0b4e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 1.75h6q1.76 0 3.005 1.245T19.25 6v12q0 1.76-1.245 3.005T15 22.25H9q-1.76 0-3.005-1.245T4.75 18V6q0-1.76 1.245-3.005T9 1.75");
}

</style>
