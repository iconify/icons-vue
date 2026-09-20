<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fm3yc7kia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-move-left-16-regular" /></template>
<style>
.fm3yc7kia {
  fill: currentColor;
  d: path("M2 13.5a.5.5 0 0 0 1 0v-11a.5.5 0 0 0-1 0zm12-9A2.5 2.5 0 0 0 11.5 2h-5a.5.5 0 0 0-.5.5V5a1.495 1.495 0 0 1 1.415 1H10v4H7.415A1.495 1.495 0 0 1 6 11v2.5a.5.5 0 0 0 .5.5h5a2.5 2.5 0 0 0 2.5-2.5zM10 13H7v-2h3zM7 5V3h3v2zm6 1v4h-2V6zm0 5v.5a1.5 1.5 0 0 1-1.5 1.5H11v-2zm0-6h-2V3h.5A1.5 1.5 0 0 1 13 4.5zM6.354 6.146a.5.5 0 0 1 0 .708l-.647.646H7.5a.5.5 0 0 1 0 1H5.707l.647.646a.5.5 0 1 1-.708.708l-1.5-1.5a.5.5 0 0 1 0-.708l1.5-1.5a.5.5 0 0 1 .708 0");
}

</style>
