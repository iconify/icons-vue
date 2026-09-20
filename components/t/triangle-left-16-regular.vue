<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g6a333e3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:triangle-left-16-regular" /></template>
<style>
.g6a333e3n {
  fill: currentColor;
  d: path("M1.777 9.313a1.5 1.5 0 0 1 0-2.629l9.999-5.5A1.5 1.5 0 0 1 13.999 2.5v10.999a1.5 1.5 0 0 1-2.223 1.314zM2.26 7.56a.5.5 0 0 0 0 .877l9.999 5.499a.5.5 0 0 0 .74-.438V2.499a.5.5 0 0 0-.74-.438z");
}

</style>
