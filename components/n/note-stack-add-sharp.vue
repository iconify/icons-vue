<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sut3pw0gz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:note-stack-add-sharp" /></template>
<style>
.sut3pw0gz {
  fill: currentColor;
  d: path("M7 22V6.975h15V17l-5 5zm-2.7-2.925L1.675 4.3L16.45 1.675L17.05 5H5v13.95zm9.2-.575h2v-3h3v-2h-3v-3h-2v3h-3v2h3z");
}

</style>
