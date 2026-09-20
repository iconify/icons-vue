<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgt861d3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tooltip-2-rounded" /></template>
<style>
.sgt861d3v {
  fill: currentColor;
  d: path("M6.5 13.75h7v-1h-7zm0-3h11v-1h-11zm0-3h11v-1h-11zM4.616 17.5q-.667 0-1.141-.475T3 15.886V4.615q0-.666.475-1.14T4.615 3h14.77q.666 0 1.14.475T21 4.615v11.27q0 .666-.475 1.14t-1.14.475H14.29l-1.62 2.462q-.13.186-.295.28t-.376.093t-.376-.094t-.295-.28L9.709 17.5z");
}

</style>
