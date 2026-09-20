<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vj1nik8tu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:rear-camera-sharp" /></template>
<style>
.vj1nik8tu {
  fill: currentColor;
  d: path("M17.213 7.713Q17.5 7.425 17.5 7t-.288-.712T16.5 6t-.712.288T15.5 7t.288.713T16.5 8t.713-.288M13 19h7V5h-7zM2 21v-8h4.2l-1.6 1.6L6 16l4-4l-4-4l-1.4 1.4L6.2 11H2V3h20v18z");
}

</style>
