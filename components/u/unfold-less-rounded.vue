<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0jm3j8ly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:unfold-less-rounded" /></template>
<style>
.i0jm3j8ly {
  fill: currentColor;
  d: path("m12 16.9l-2.4 2.4q-.275.275-.7.275t-.7-.275t-.275-.7t.275-.7l3.1-3.1q.15-.15.325-.212t.375-.063t.375.063t.325.212l3.1 3.1q.275.275.275.7t-.275.7t-.7.275t-.7-.275zm0-9.8l2.4-2.4q.275-.275.7-.275t.7.275t.275.7t-.275.7l-3.1 3.1q-.15.15-.325.213T12 9.475t-.375-.062T11.3 9.2L8.2 6.1q-.275-.275-.275-.7t.275-.7t.7-.275t.7.275z");
}

</style>
