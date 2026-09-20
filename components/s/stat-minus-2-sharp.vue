<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htsz9iwyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stat-minus-2-sharp" /></template>
<style>
.htsz9iwyu {
  fill: currentColor;
  d: path("m12 18.27l-5.308-5.308l.708-.708l4.6 4.594l4.6-4.594l.708.707zm0-5.962L6.692 7l.708-.708l4.6 4.595l4.6-4.595l.708.708z");
}

</style>
