<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="rs2mvsbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rectangle-portrait-28-filled" /></template>
<style>
.rs2mvsbcp {
  fill: currentColor;
  d: path("M4.002 22.248a3.75 3.75 0 0 0 3.75 3.75h12.5a3.75 3.75 0 0 0 3.75-3.75V5.752a3.75 3.75 0 0 0-3.75-3.75h-12.5a3.75 3.75 0 0 0-3.75 3.75z");
}

</style>
