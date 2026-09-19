<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rf0ju4blx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-pause-presentation" /></template>
<style>
.rf0ju4blx {
  fill: currentColor;
  d: path("M1 3v18h22V3zm20 16H3V5h18zM9 8h2v8H9zm4 0h2v8h-2z");
}

</style>
