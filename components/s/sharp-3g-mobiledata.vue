<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lr49rrbcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-3g-mobiledata" /></template>
<style>
.lr49rrbcw {
  fill: currentColor;
  d: path("M3 7v2h5v2H4v2h4v2H3v2h7V7zm18 4v6h-9V7h9v2h-7v6h5v-2h-2.5v-2z");
}

</style>
