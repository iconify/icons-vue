<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbq63-voi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:photo-frame-sharp" /></template>
<style>
.tbq63-voi {
  fill: currentColor;
  d: path("M4.846 19.423V18H2V5h20v13h-2.846v1.423zM6.404 14.5h11.212l-3.5-4.673l-3.116 4l-2.096-2.539z");
}

</style>
