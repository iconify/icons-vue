<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irhxq-bln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-sticky-note-2" /></template>
<style>
.irhxq-bln {
  fill: currentColor;
  d: path("M2.99 3L3 21h12l6-6V3zM7 8h10v2H7zm5 6H7v-2h5zm2 5.5V14h5.5z");
}

</style>
