<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1cf4eb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:system-update-alt-sharp" /></template>
<style>
.g1cf4eb3s {
  fill: currentColor;
  d: path("M3 19V5h5.73v1H4v12h16V6h-4.73V5H21v14zm9-4.1l-4.308-4.308l.708-.707l3.1 3.1V5h1v7.985l3.1-3.1l.708.707z");
}

</style>
