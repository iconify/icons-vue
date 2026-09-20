<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfbx2acpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:square-dot-outline" /></template>
<style>
.jfbx2acpa {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-1h14V5H5zm7-3.75q-1.362 0-2.306-.944T8.75 12t.944-2.306T12 8.75t2.306.944T15.25 12t-.944 2.306T12 15.25");
}

</style>
