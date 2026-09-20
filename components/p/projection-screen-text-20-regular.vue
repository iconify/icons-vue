<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gf9xz_idk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:projection-screen-text-20-regular" /></template>
<style>
.gf9xz_idk {
  fill: currentColor;
  d: path("M7.5 7a.5.5 0 0 0 0 1h5a.5.5 0 0 0 0-1zM6 9.5a.5.5 0 0 1 .5-.5h7a.5.5 0 0 1 0 1h-7a.5.5 0 0 1-.5-.5M7.5 11a.5.5 0 0 0 0 1h5a.5.5 0 0 0 0-1zm-5-9A1.5 1.5 0 0 0 2 4.915V12a3 3 0 0 0 3 3h4.5v2h-3a.5.5 0 0 0 0 1h7a.5.5 0 0 0 0-1h-3v-2H15a3 3 0 0 0 3-3V4.915A1.5 1.5 0 0 0 17.5 2zM3 12V5h14v7a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2");
}

</style>
