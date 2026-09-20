<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3wjtrwtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tour" /></template>
<style>
.h3wjtrwtr {
  fill: currentColor;
  d: path("M5.5 21.5v-19h1v2h13.77L18.46 9l1.808 4.5H6.5v8zm8.066-11.434Q14 9.633 14 9t-.434-1.066T12.5 7.5t-1.066.434Q11 8.367 11 9t.434 1.066t1.066.434t1.066-.434");
}

</style>
