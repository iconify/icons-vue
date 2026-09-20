<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zpmokub1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sound-wave-circle-add-20-regular" /></template>
<style>
.zpmokub1d {
  fill: currentColor;
  d: path("M14.5 10a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M9.996 1.999a8 8 0 0 1 8 8q-.001.126-.007.25a5.5 5.5 0 0 0-1.006-.656a7 7 0 1 0-7.39 7.393q.276.541.658 1.006q-.127.006-.255.007a8 8 0 1 1 0-16M14.5 12a.5.5 0 0 0-.5.5V14h-1.5a.5.5 0 0 0 0 1H14v1.5a.5.5 0 0 0 1 0V15h1.5a.5.5 0 0 0 0-1H15v-1.5a.5.5 0 0 0-.5-.5m-6-5a.5.5 0 0 1 .5.5v5a.5.5 0 0 1-1 0v-5a.5.5 0 0 1 .5-.5M6 8.5a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-1 0V9a.5.5 0 0 1 .5-.5m5-.5a.5.5 0 0 1 .5.5v1.39a5.5 5.5 0 0 0-1 .837V8.5A.5.5 0 0 1 11 8m2.5-1a.5.5 0 0 1 .5.5v1.523q-.517.047-1 .185V7.5a.5.5 0 0 1 .5-.5");
}

</style>
