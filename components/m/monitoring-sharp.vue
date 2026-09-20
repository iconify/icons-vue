<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thez-bcbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:monitoring-sharp" /></template>
<style>
.thez-bcbf {
  fill: currentColor;
  d: path("M3 21v-2l2-2v4zm4 0v-6l2-2v8zm4 0v-8l2 2.025V21zm4 0v-5.975l2-2V21zm4 0V11l2-2v12zM3 15.825V13l7-7l4 4l7-7v2.825l-7 7l-4-4z");
}

</style>
