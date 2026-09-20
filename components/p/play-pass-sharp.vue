<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehdggtfkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:play-pass-sharp" /></template>
<style>
.ehdggtfkq {
  fill: currentColor;
  d: path("M12 20q-.825 0-1.413.588T10 22H5V2h5q0 .825.588 1.413T12 4q.825 0 1.413-.588T14 2h5v20h-5q0-.825-.588-1.413T12 20Z");
}

</style>
