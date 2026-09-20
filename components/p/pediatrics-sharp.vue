<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2d6otksi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pediatrics-sharp" /></template>
<style>
.y2d6otksi {
  fill: currentColor;
  d: path("M7.885 7.577v-1H11.5V3.769h1v2.808h3.616v1zm1.73 13q-.666 0-1.14-.475T8 18.963v-2.058h3.5v-1H8V13.25h3.5v-1H8V11q0-1.01.707-1.716t1.716-.707h3.154q1.01 0 1.716.707T16 11v7.962q0 .666-.475 1.14t-1.14.475z");
}

</style>
