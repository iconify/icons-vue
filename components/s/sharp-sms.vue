<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bld455qbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-sms" /></template>
<style>
.bld455qbr {
  fill: currentColor;
  d: path("M22 2H2v20l4-4h16zM9 11H7V9h2zm4 0h-2V9h2zm4 0h-2V9h2z");
}

</style>
