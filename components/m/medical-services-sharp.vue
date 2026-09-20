<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqt4zjz3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:medical-services-sharp" /></template>
<style>
.aqt4zjz3r {
  fill: currentColor;
  d: path("M3 21V7h6V4h6v3h6v14zm7-14h4V5h-4zm1.5 7.5v3h1v-3h3v-1h-3v-3h-1v3h-3v1z");
}

</style>
