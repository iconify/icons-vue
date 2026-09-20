<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ct7fs6b3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:shifts-add-20-regular" /></template>
<style>
.ct7fs6b3q {
  fill: currentColor;
  d: path("M6 3a3 3 0 0 0-3 3v3.6a5.5 5.5 0 0 1 1-.393V6a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2h-3.207q-.149.524-.393 1H14a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3zm-.5 16a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9m0-7a.5.5 0 0 1 .5.5V14h1.5a.5.5 0 0 1 0 1H6v1.5a.5.5 0 0 1-1 0V15H3.5a.5.5 0 0 1 0-1H5v-1.5a.5.5 0 0 1 .5-.5M11 6.5a.5.5 0 0 0-1 0v3a.5.5 0 0 0 .5.5h2a.5.5 0 0 0 0-1H11z");
}

</style>
