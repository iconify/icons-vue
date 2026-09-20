<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcre_5bdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:turn-right" /></template>
<style>
.dcre_5bdy {
  fill: currentColor;
  d: path("M7 20v-9q0-.825.588-1.412T9 9h8.2l-1.6-1.6L17 6l4 4l-4 4l-1.4-1.4l1.6-1.6H9v9z");
}

</style>
