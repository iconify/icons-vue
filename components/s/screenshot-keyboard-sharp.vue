<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_cxtab2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:screenshot-keyboard-sharp" /></template>
<style>
.g_cxtab2o {
  fill: currentColor;
  d: path("M14.825 14.825Q16 13.65 16 12t-1.175-2.825T12 8T9.175 9.175T8 12t1.175 2.825T12 16t2.825-1.175M2 20V4h20v16z");
}

</style>
