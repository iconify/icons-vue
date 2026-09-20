<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l37nn-baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:table" /></template>
<style>
.l37nn-baw {
  fill: currentColor;
  d: path("M11.5 14.885H4v3.5q0 .666.475 1.14t1.14.475H11.5zm1 0V20h5.885q.666 0 1.14-.475t.475-1.14v-3.5zm-1-1V8.769H4v5.116zm1 0H20V8.769h-7.5zM4 7.769h16V5.615q0-.666-.475-1.14T18.386 4H5.615q-.666 0-1.14.475T4 5.615z");
}

</style>
