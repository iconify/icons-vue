<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0r5mrb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:power-input-sharp" /></template>
<style>
.r0r5mrb_e {
  fill: currentColor;
  d: path("M3 14.5v-1h4.058v1zm0-4v-1h17v1zm6.442 4v-1h4.116v1zm6.5 0v-1H20v1z");
}

</style>
