<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gk881qbnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:padding-down-24-filled" /></template>
<style>
.gk881qbnz {
  fill: currentColor;
  d: path("M4 3a1 1 0 0 0 1 1h14a1 1 0 1 0 0-2H5a1 1 0 0 0-1 1m0 18a1 1 0 0 0 1 1h1.75a1 1 0 1 0 0-2H5a1 1 0 0 0-1 1m5.25 0a1 1 0 0 0 1 1h3.5a1 1 0 1 0 0-2h-3.5a1 1 0 0 0-1 1m7 0a1 1 0 0 0 1 1H19a1 1 0 1 0 0-2h-1.75a1 1 0 0 0-1 1m1.457-7.293l-5 5a1 1 0 0 1-1.414 0l-5-5a1 1 0 1 1 1.414-1.414L11 15.586V6a1 1 0 1 1 2 0v9.586l3.293-3.293a1 1 0 0 1 1.414 1.414");
}

</style>
