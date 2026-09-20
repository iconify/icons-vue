<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpb4fpjnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:open-jam-sharp" /></template>
<style>
.bpb4fpjnf {
  fill: currentColor;
  d: path("M6 21v-2h7v-7.2l1.6 1.6L16 12l-4-4l-4 4l1.4 1.4l1.6-1.6V16H2V3h20v13h-7v3h3v2z");
}

</style>
