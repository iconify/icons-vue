<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pha4gg2xa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:status-online" /></template>
<style>
.pha4gg2xa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 12q0 3.21 2.27 5.48T12 19.75t5.48-2.27T19.75 12t-2.27-5.48T12 4.25T6.52 6.52T4.25 12");
}

</style>
