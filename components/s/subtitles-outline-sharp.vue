<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cloqq6bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:subtitles-outline-sharp" /></template>
<style>
.cloqq6bez {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-2h16V6H4zm0 0V6zm2-2h8v-2H6zm10 0h2v-2h-2zM6 12h2v-2H6zm4 0h8v-2h-8z");
}

</style>
