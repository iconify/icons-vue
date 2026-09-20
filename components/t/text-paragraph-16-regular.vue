<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o64cu3_mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-paragraph-16-regular" /></template>
<style>
.o64cu3_mh {
  fill: currentColor;
  d: path("M2.5 3a.5.5 0 0 0 0 1h11a.5.5 0 0 0 0-1zm9 11a.5.5 0 0 0 .5-.5V6h1v7.5a.5.5 0 0 0 1 0V6h.5a.5.5 0 0 0 0-1H11a2.998 2.998 0 1 0 0 6v2.5a.5.5 0 0 0 .5.5M10 6.268A2 2 0 0 1 11 6v4a1.99 1.99 0 0 1-1.732-1A2 2 0 0 1 9 8a1.99 1.99 0 0 1 1-1.732M7.535 6H2.5a.5.5 0 0 0 0 1h4.626q.138-.534.41-1m-.409 3q.138.534.41 1H2.5a.5.5 0 0 1 0-1z");
}

</style>
