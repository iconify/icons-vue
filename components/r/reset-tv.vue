<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7ctlirfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:reset-tv" /></template>
<style>
.l7ctlirfn {
  fill: currentColor;
  d: path("M9 20v-2H4.616q-.667 0-1.141-.475T3 16.386V5.615q0-.666.475-1.14T4.615 4h14.77q.666 0 1.14.475T21 5.615V10.5h-9.392l2.35-2.35l-.708-.708L9.692 11l3.558 3.558l.708-.708l-2.35-2.35H21v4.885q0 .666-.475 1.14t-1.14.475H15v2z");
}

</style>
