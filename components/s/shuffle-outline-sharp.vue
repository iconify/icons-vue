<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6_lsob-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shuffle-outline-sharp" /></template>
<style>
.f6_lsob-v {
  fill: currentColor;
  d: path("M14 20v-2h2.6l-3.175-3.175L14.85 13.4L18 16.55V14h2v6zm-8.6 0L4 18.6L16.6 6H14V4h6v6h-2V7.4zm3.775-9.425L4 5.4L5.4 4l5.175 5.175z");
}

</style>
