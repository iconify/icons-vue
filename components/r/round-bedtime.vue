<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4x1nebql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-bedtime" /></template>
<style>
.n4x1nebql {
  fill: currentColor;
  d: path("M11.65 3.46c.27-.71-.36-1.45-1.12-1.34c-5.52.8-9.47 6.07-8.34 11.88c.78 4.02 4.09 7.21 8.14 7.87c3.74.61 7.16-.87 9.32-3.44c.48-.57.19-1.48-.55-1.62c-6.02-1.15-9.68-7.54-7.45-13.35");
}

</style>
