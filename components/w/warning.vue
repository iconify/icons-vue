<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcf_ffb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:warning" /></template>
<style>
.pcf_ffb0v {
  fill: currentColor;
  d: path("M1 21L12 2l11 19zm11.713-3.287Q13 17.425 13 17t-.288-.712T12 16t-.712.288T11 17t.288.713T12 18t.713-.288M11 15h2v-5h-2z");
}

</style>
