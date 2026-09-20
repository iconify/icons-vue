<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kj39jfl1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sd-outline-sharp" /></template>
<style>
.kj39jfl1q {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-2h16V6H4zm2-3h5v-3.5H7.5v-1h2v.5H11V9H6v3.5h3.5v1h-2V13H6zm7 0h4.25l.75-.75v-4.5L17.25 9H13zm1.5-1.5v-3h2v3zM4 18V6z");
}

</style>
