<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s347_mkhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-signal-cellular-alt-2-bar" /></template>
<style>
.s347_mkhk {
  fill: currentColor;
  d: path("M6.5 20c-.83 0-1.5-.67-1.5-1.5v-3c0-.83.67-1.5 1.5-1.5s1.5.67 1.5 1.5v3c0 .83-.67 1.5-1.5 1.5m6 0c-.83 0-1.5-.67-1.5-1.5v-8c0-.83.67-1.5 1.5-1.5s1.5.67 1.5 1.5v8c0 .83-.67 1.5-1.5 1.5");
}

</style>
