<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cfxk9j90b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-clip-off-20-regular" /></template>
<style>
.cfxk9j90b {
  fill: currentColor;
  d: path("M2.854 2.146a.5.5 0 1 0-.708.708l.739.738A2.5 2.5 0 0 0 2 5.5v9A2.5 2.5 0 0 0 4.5 17h11q.362-.001.695-.098l.951.952a.5.5 0 0 0 .708-.708zM15.293 16H4.5A1.5 1.5 0 0 1 3 14.5v-9c0-.489.234-.923.596-1.197L8 8.707v3.943a.5.5 0 0 0 .776.417l2.156-1.428zM9.918 7.797l2.716 2.716l.142-.095a.5.5 0 0 0-.01-.84zM17 14.5q0 .175-.039.34l.777.776A2.5 2.5 0 0 0 18 14.5v-9A2.5 2.5 0 0 0 15.5 3H5.121l1 1H15.5A1.5 1.5 0 0 1 17 5.5z");
}

</style>
