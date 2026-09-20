<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v7q93wbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:phone-32-regular" /></template>
<style>
.v7q93wbsb {
  fill: currentColor;
  d: path("M10.25 2A3.25 3.25 0 0 0 7 5.25v21.5A3.25 3.25 0 0 0 10.25 30h11.5A3.25 3.25 0 0 0 25 26.75V5.25A3.25 3.25 0 0 0 21.75 2zM9 5.25C9 4.56 9.56 4 10.25 4h11.5c.69 0 1.25.56 1.25 1.25v21.5c0 .69-.56 1.25-1.25 1.25h-11.5C9.56 28 9 27.44 9 26.75zM14 24a1 1 0 1 0 0 2h4a1 1 0 1 0 0-2z");
}

</style>
