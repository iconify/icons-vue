<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uljyvtl_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tab-desktop-copy-20-filled" /></template>
<style>
.uljyvtl_t {
  fill: currentColor;
  d: path("M5 4.5A2.5 2.5 0 0 1 7.5 2H9v2.5A1.5 1.5 0 0 0 10.5 6H18v6.5a2.5 2.5 0 0 1-2.5 2.5h-8A2.5 2.5 0 0 1 5 12.5zm5 0V2h5.5A2.5 2.5 0 0 1 18 4.5V5h-7.5a.5.5 0 0 1-.5-.5M12.5 18a2.5 2.5 0 0 0 2.45-2H7.5A3.5 3.5 0 0 1 4 12.5V5.05A2.5 2.5 0 0 0 2 7.5V14a4 4 0 0 0 4 4z");
}

</style>
