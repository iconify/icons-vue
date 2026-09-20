<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="afz3xub1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-bullet-list-square-clock-28-filled" /></template>
<style>
.afz3xub1j {
  fill: currentColor;
  d: path("M20.5 14a6.5 6.5 0 1 1 0 13a6.5 6.5 0 0 1 0-13m.75-11A3.75 3.75 0 0 1 25 6.75v7.75a7.47 7.47 0 0 0-4.5-1.5a7.5 7.5 0 0 0-2.692.5H12.75a.75.75 0 0 0 0 1.5h2.652A7.48 7.48 0 0 0 13 20.5c0 1.689.558 3.247 1.5 4.5H6.75A3.75 3.75 0 0 1 3 21.25V6.75A3.75 3.75 0 0 1 6.75 3zm-.75 13.5a.5.5 0 0 0-.5.5v3.5a.5.5 0 0 0 .5.5h3a.5.5 0 0 0 0-1H21v-3a.5.5 0 0 0-.5-.5M8.75 18a1.25 1.25 0 1 0 0 2.5a1.25 1.25 0 0 0 0-2.5m0-5a1.25 1.25 0 1 0 0 2.5a1.25 1.25 0 0 0 0-2.5m0-5a1.25 1.25 0 1 0 0 2.5a1.25 1.25 0 0 0 0-2.5m4 .5a.75.75 0 0 0 0 1.5h7.5a.75.75 0 0 0 0-1.5z");
}

</style>
