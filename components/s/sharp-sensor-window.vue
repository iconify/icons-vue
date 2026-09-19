<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ox8nwiisu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-sensor-window" /></template>
<style>
.ox8nwiisu {
  fill: currentColor;
  d: path("M18 4v16H6V4zM4 2v20h16V2zm3 17h10v-6H7zm3-9h4v1h3V5H7v6h3z");
}

</style>
