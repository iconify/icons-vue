<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcy8u1b1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-perm-media" /></template>
<style>
.kcy8u1b1k {
  fill: currentColor;
  d: path("M2 6H0v16h20v-2H2zm22-2H14l-2-2H4v16h20zM7 15l4.5-6l3.5 4.51l2.5-3.01L21 15z");
}

</style>
