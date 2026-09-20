<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgcybubyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:phone-page-header-24-filled" /></template>
<style>
.lgcybubyf {
  fill: currentColor;
  d: path("M18 6.005V19.75A2.25 2.25 0 0 1 15.75 22h-7.5A2.25 2.25 0 0 1 6 19.75V6.005zM15.75 2A2.25 2.25 0 0 1 18 4.25V5H6v-.75A2.25 2.25 0 0 1 8.25 2z");
}

</style>
