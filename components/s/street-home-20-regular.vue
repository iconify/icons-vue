<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r5a70acak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:street-home-20-regular" /></template>
<style>
.r5a70acak {
  fill: currentColor;
  d: path("M17.5 16a.5.5 0 0 1 0 1h-15a.5.5 0 0 1 0-1zM4.5 3A2.5 2.5 0 0 1 5 7.95V14h2V9.501c0-.438.191-.855.523-1.14l3.5-3a1.5 1.5 0 0 1 1.954 0l3.5 3c.332.285.523.702.523 1.14V14h.5a.5.5 0 0 1 0 1h-15a.5.5 0 0 1 0-1H4V7.95A2.5 2.5 0 0 1 4.5 3m7.825 3.121a.5.5 0 0 0-.65 0l-3.5 3a.5.5 0 0 0-.175.38V14h2v-2.5a1.5 1.5 0 0 1 1.5-1.5h1a1.5 1.5 0 0 1 1.5 1.5V14h2V9.501a.5.5 0 0 0-.175-.38zM11.5 11a.5.5 0 0 0-.5.5V14h2v-2.5a.5.5 0 0 0-.5-.5zm-7-7a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3");
}

</style>
