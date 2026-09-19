<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thm_z2b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-phone-android" /></template>
<style>
.thm_z2b0l {
  fill: currentColor;
  d: path("M19 1H5v22h14zm-5 20h-4v-1h4zm3-3H7V4h10z");
}

</style>
