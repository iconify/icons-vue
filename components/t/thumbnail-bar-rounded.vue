<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6aflmb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:thumbnail-bar-rounded" /></template>
<style>
.e6aflmb2e {
  fill: currentColor;
  d: path("M4.616 19q-.667 0-1.141-.475T3 17.386V6.615q0-.666.475-1.14T4.615 5H8v14zM9 19V5h10.385q.666 0 1.14.475T21 6.615v10.77q0 .666-.475 1.14t-1.14.475z");
}

</style>
