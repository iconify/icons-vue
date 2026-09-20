<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc-p4bc_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-add-t-24-filled" /></template>
<style>
.jc-p4bc_z {
  fill: currentColor;
  d: path("M3.75 5a1 1 0 0 1 1-1h12.5a1 1 0 0 1 1 1v2a1 1 0 1 1-2 0V6H12v8.034a6.47 6.47 0 0 0-1 3.466c0 .886.177 1.73.498 2.5H9a1 1 0 1 1 0-2h1V6H5.75v1a1 1 0 0 1-2 0zM23 17.5a5.5 5.5 0 1 0-11 0a5.5 5.5 0 0 0 11 0m-5 .5l.001 2.503a.5.5 0 1 1-1 0V18h-2.505a.5.5 0 0 1 0-1H17v-2.5a.5.5 0 1 1 1 0V17h2.497a.5.5 0 0 1 0 1z");
}

</style>
