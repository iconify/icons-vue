<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z4lsmunig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:window-new-rotate-180-16-filled" /></template>
<style>
.z4lsmunig {
  fill: currentColor;
  d: path("M4.5 14A2.5 2.5 0 0 1 2 11.5v-5c0-1.225.881-2.242 2.044-2.456A2.5 2.5 0 0 1 6.5 2H10a4 4 0 0 1 4 4v3.5a2.5 2.5 0 0 1-2.043 2.457A2.5 2.5 0 0 1 9.5 14zm7.5-3.087A1.5 1.5 0 0 0 13 9.5V6a3 3 0 0 0-3-3H6.5a1.5 1.5 0 0 0-1.413 1H9.5A2.5 2.5 0 0 1 12 6.5zM8 11a.5.5 0 0 0 0-1H6.707l2.647-2.646a.5.5 0 1 0-.708-.708L6 9.293V8a.5.5 0 0 0-1 0v2.5a.5.5 0 0 0 .5.5z");
}

</style>
