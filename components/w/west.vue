<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntmeapo2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:west" /></template>
<style>
.ntmeapo2u {
  fill: currentColor;
  d: path("M9.346 18.327L3 11.981l6.346-6.346l.689.688l-5.152 5.158h16.136v1H4.902l5.158 5.158z");
}

</style>
