<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xe25o9bat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:playlist-add-circle" /></template>
<style>
.xe25o9bat {
  fill: currentColor;
  d: path("M15 17h2v-2h2v-2h-2v-2h-2v2h-2v2h2zm-8-2h3v-2H7zm0-3h7v-2H7zm0-3h7V7H7zm5 13q-2.075 0-3.9-.788t-3.175-2.137T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22");
}

</style>
