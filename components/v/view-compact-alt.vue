<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq_lxvlam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-compact-alt" /></template>
<style>
.uq_lxvlam {
  fill: currentColor;
  d: path("M8.25 15.75h3v-3h-3zm0-4.5h3v-3h-3zm4.5 4.5h3v-3h-3zm0-4.5h3v-3h-3zM4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19z");
}

</style>
