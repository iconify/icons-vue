<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yw0i55b1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:variables-outline-rounded" /></template>
<style>
.yw0i55b1e {
  fill: currentColor;
  d: path("M3 16V8q0-.425.288-.712T4 7h16q.425 0 .713.288T21 8v8q0 .425-.288.713T20 17H4q-.425 0-.712-.288T3 16m2-1h14V9H5zm0 0V9z");
}

</style>
