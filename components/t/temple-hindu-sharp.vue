<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8loqt5ak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:temple-hindu-sharp" /></template>
<style>
.l8loqt5ak {
  fill: currentColor;
  d: path("m7.8 7l1.175-3.875V1h2v2H13V1h2v2l1.2 4zM2 22V11h2v2h16v-2h2v11h-9v-5h-2v5zm4.6-11l.6-2h9.6l.6 2z");
}

</style>
