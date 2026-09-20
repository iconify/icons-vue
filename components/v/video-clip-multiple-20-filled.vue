<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cyoqw4sjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-clip-multiple-20-filled" /></template>
<style>
.cyoqw4sjk {
  fill: currentColor;
  d: path("M4.5 3A2.5 2.5 0 0 0 2 5.5v7A2.5 2.5 0 0 0 4.5 15h9a2.5 2.5 0 0 0 2.5-2.5v-7A2.5 2.5 0 0 0 13.5 3zM7 6.756a.75.75 0 0 1 1.171-.62l3.61 2.451a.5.5 0 0 1 .001.827l-3.61 2.458A.75.75 0 0 1 7 11.252zM6.5 17a2.5 2.5 0 0 1-2-1H14a3 3 0 0 0 3-3V5.5c.607.456 1 1.182 1 2V13a4 4 0 0 1-4 4z");
}

</style>
