<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wme2129eb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tools-level-rounded" /></template>
<style>
.wme2129eb {
  fill: currentColor;
  d: path("M4.616 16q-.667 0-1.141-.475T3 14.385v-4.77q0-.666.475-1.14T4.615 8h14.77q.666 0 1.14.475T21 9.615v4.77q0 .666-.475 1.14t-1.14.475zM9.5 12h2V9h-2q-.6 0-1.05.45T8 10.5t.45 1.05T9.5 12m3 0h2q.6 0 1.05-.45T16 10.5t-.45-1.05T14.5 9h-2z");
}

</style>
