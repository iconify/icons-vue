<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nt59cobke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:ticket-horizontal-20-filled" /></template>
<style>
.nt59cobke {
  fill: currentColor;
  d: path("M16 5a2 2 0 0 1 2 2v.5a.773.773 0 0 1-.694.76a1.75 1.75 0 0 0 0 3.48a.77.77 0 0 1 .694.76v.5a2 2 0 0 1-2 2h-3v-1.5a.5.5 0 0 0-1 0V15H4a2 2 0 0 1-2-2v-.5c0-.426.339-.721.694-.76a1.75 1.75 0 0 0 0-3.48A.773.773 0 0 1 2 7.5V7a2 2 0 0 1 2-2h8v1.5a.5.5 0 0 0 1 0V5zm-3.5 3.5a.5.5 0 0 0-.5.5v2a.5.5 0 0 0 1 0V9a.5.5 0 0 0-.5-.5");
}

</style>
