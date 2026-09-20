<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d9yh4gb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-6-20-regular" /></template>
<style>
.d9yh4gb7d {
  fill: currentColor;
  d: path("M6 6a4 4 0 1 1 8 0a4 4 0 0 1-8 0m4-3a3 3 0 1 0 0 6a3 3 0 0 0 0-6M3 13c0-1.113.903-2 2.009-2h9.042a3.5 3.5 0 0 0-.714 1H5.009C4.448 12 4 12.447 4 13c0 1.309.622 2.284 1.673 2.953C6.743 16.636 8.265 17 10 17c1.108 0 2.129-.148 3-.433q.012.522.165.997c-.961.294-2.04.436-3.165.436c-1.855 0-3.583-.386-4.865-1.203C3.833 15.967 3 14.69 3 13m12 .5a1.5 1.5 0 0 1 2.625-.992a.5.5 0 0 0 .75-.662A2.5 2.5 0 0 0 14 13.5v3a2.5 2.5 0 1 0 1-2zm1.5 4.5a1.5 1.5 0 1 1 0-3a1.5 1.5 0 0 1 0 3");
}

</style>
