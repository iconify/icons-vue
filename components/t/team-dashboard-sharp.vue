<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbxu_vb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:team-dashboard-sharp" /></template>
<style>
.pbxu_vb6p {
  fill: currentColor;
  d: path("M10 21v-8.25H3V21zm2 0h9v-8.25h-9zM3 10.75h18V3H3z");
}

</style>
