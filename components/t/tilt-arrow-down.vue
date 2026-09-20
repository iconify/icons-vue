<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxx3-rmcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tilt-arrow-down" /></template>
<style>
.bxx3-rmcm {
  fill: currentColor;
  d: path("M6.616 20q-.691 0-1.153-.462T5 18.384V5.616q0-.691.463-1.153T6.616 4h10.788q.69 0 1.153.463t.462 1.153v12.769q0 .69-.462 1.153T17.404 20zm4.903-6.536L9.4 11.35l-.708.708l3.327 3.327l3.289-3.289l-.708-.713l-2.08 2.08V8.77h-1z");
}

</style>
