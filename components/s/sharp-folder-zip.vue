<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxm4o4e2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-folder-zip" /></template>
<style>
.yxm4o4e2n {
  fill: currentColor;
  d: path("m12 6l-2-2H2v16h20V6zm6 6h-2v2h2v2h-2v2h-2v-2h2v-2h-2v-2h2v-2h-2V8h2v2h2z");
}

</style>
