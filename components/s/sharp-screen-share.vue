<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqv-mp30n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-screen-share" /></template>
<style>
.yqv-mp30n {
  fill: currentColor;
  d: path("m20 18l2-2V4H2v12l2 2H0v2h24v-2zm-7-3.53v-2.19c-2.78 0-4.61.85-6 2.72c.56-2.67 2.11-5.33 6-5.87V7l4 3.73z");
}

</style>
