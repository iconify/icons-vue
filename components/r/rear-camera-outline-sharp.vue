<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_4wq7beh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:rear-camera-outline-sharp" /></template>
<style>
.r_4wq7beh {
  fill: currentColor;
  d: path("m6 16l4-4l-4-4l-1.4 1.4L6.2 11H2v2h4.2l-1.6 1.6zm11.213-8.287Q17.5 7.425 17.5 7t-.288-.712T16.5 6t-.712.288T15.5 7t.288.713T16.5 8t.713-.288M13 19h7V5h-7zM2 21v-6h2v4h7V5H4v4H2V3h20v18zm9-2V5z");
}

</style>
