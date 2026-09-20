<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f60e3dv8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:strategy-outline-sharp" /></template>
<style>
.f60e3dv8q {
  fill: currentColor;
  d: path("M5.5 11L2 9V5l3.5-2L9 5v4zm0-2.3L7 7.85v-1.7L5.5 5.3L4 6.15v1.7zm11 3.075V9.45L20 11.5v7L14 22l-6-3.5v-7l3.5-2.05v2.325l-1.5.875v4.7l4 2.325l4-2.325v-4.7zM13 14V2h9l-2 3l2 3h-7v6zM5.5 7");
}

</style>
