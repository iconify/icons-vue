<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nk5agebqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:process-chart-sharp" /></template>
<style>
.nk5agebqs {
  fill: currentColor;
  d: path("m3.646 17.777l-.896-.439L8.308 6.224l.896.438zm6.023 0l-.896-.438l5.558-11.116l.896.438zm6.023 0l-.896-.438l5.558-11.116l.896.439z");
}

</style>
