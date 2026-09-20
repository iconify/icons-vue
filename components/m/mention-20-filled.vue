<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jg92w0pep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mention-20-filled" /></template>
<style>
.jg92w0pep {
  fill: currentColor;
  d: path("M10 2a8 8 0 0 1 8 8c0 2.475-1.488 3.999-3.25 3.999c-1.027 0-1.96-.518-2.56-1.44C11.566 13.423 10.622 14 9.5 14C7.454 14 6 12.087 6 10s1.454-4 3.5-4c.765 0 1.447.268 2.001.712A.75.75 0 0 1 13 6.75V10c0 1.857 1.012 2.499 1.75 2.499S16.5 11.857 16.5 10a6.5 6.5 0 1 0-4.562 6.204a.84.84 0 0 1 .852.191c.378.378.272 1.015-.234 1.186A8 8 0 1 1 10 2m-.5 5.5c-.992 0-2 .997-2 2.5s1.008 2.5 2 2.5s2-.997 2-2.5s-1.008-2.5-2-2.5");
}

</style>
