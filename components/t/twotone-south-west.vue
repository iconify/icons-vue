<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttb05hbuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-south-west" /></template>
<style>
.ttb05hbuh {
  fill: currentColor;
  d: path("M15 19v-2H8.41L20 5.41L18.59 4L7 15.59V9H5v10z");
}

</style>
