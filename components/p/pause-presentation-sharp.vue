<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi1pf1b0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pause-presentation-sharp" /></template>
<style>
.hi1pf1b0e {
  fill: currentColor;
  d: path("M9 16h2V8H9zm4 0h2V8h-2zM2 20V4h20v16z");
}

</style>
