<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrgyses5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:more-vertical" /></template>
<style>
.hrgyses5v {
  fill: currentColor;
  d: path("M14 5C14 6.1045 13.1045 7 12 7C10.8955 7 10 6.1045 10 5C10 3.8955 10.8955 3 12 3C13.1045 3 14 3.8955 14 5ZM14 12C14 13.1045 13.1045 14 12 14C10.8955 14 10 13.1045 10 12C10 10.8955 10.8955 10 12 10C13.1045 10 14 10.8955 14 12ZM14 19C14 20.1045 13.1045 21 12 21C10.8955 21 10 20.1045 10 19C10 17.8955 10.8955 17 12 17C13.1045 17 14 17.8955 14 19Z");
}

</style>
