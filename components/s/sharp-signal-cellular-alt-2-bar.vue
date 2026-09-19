<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8vvoplie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-signal-cellular-alt-2-bar" /></template>
<style>
.a8vvoplie {
  fill: currentColor;
  d: path("M5 14h3v6H5zm6-5h3v11h-3z");
}

</style>
