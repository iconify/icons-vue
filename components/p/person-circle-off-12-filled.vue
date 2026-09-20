<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ym7l9imie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-circle-off-12-filled" /></template>
<style>
.ym7l9imie {
  fill: currentColor;
  d: path("M1.146 1.146a.5.5 0 0 1 .708 0l9 9a.5.5 0 0 1-.707.707l-.985-.984A4.97 4.97 0 0 1 6 11a5 5 0 0 1-3.871-8.164l-.983-.982a.5.5 0 0 1 0-.708M4.776 6a.75.75 0 0 0-.56.265A.84.84 0 0 0 4 6.81v.16c0 .817.817 1.53 2 1.53c.558 0 1.03-.162 1.378-.415L5.293 6zM6 1a5 5 0 0 1 4.434 7.31l-3.67-3.668a1 1 0 0 0-1.407-1.407l-1.669-1.67A5 5 0 0 1 6 1");
}

</style>
