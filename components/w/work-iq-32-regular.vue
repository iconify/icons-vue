<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="prj-xlb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:work-iq-32-regular" /></template>
<style>
.prj-xlb7g {
  fill: currentColor;
  d: path("M16 3c7.732 0 14 6.268 14 14a9 9 0 0 1-5 8.061v.439a3.5 3.5 0 0 0 3.5 3.5h.5a1 1 0 1 1 0 2h-.5a5.5 5.5 0 0 1-5.494-5.227A9 9 0 0 1 21 26h-1.5a5.5 5.5 0 1 1 5.5-5.5v2.243A6.99 6.99 0 0 0 28 17c0-6.627-5.373-12-12-12S4 10.373 4 17v.75A4.25 4.25 0 0 0 8.25 22H11a1 1 0 1 1 0 2H8.25A6.25 6.25 0 0 1 2 17.75V17C2 9.268 8.268 3 16 3m3.5 14a3.5 3.5 0 1 0 0 7H21a7 7 0 0 0 2-.292V20.5a3.5 3.5 0 0 0-3.5-3.5");
}

</style>
