<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qmf-1lboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-move-right-16-regular" /></template>
<style>
.qmf-1lboy {
  fill: currentColor;
  d: path("M14 2.5a.5.5 0 0 0-1 0v11a.5.5 0 0 0 1 0zm-12 9A2.5 2.5 0 0 0 4.5 14h5a.5.5 0 0 0 .5-.5V11a1.495 1.495 0 0 1-1.415-1H6V6h2.585A1.495 1.495 0 0 1 10 5V2.5a.5.5 0 0 0-.5-.5h-5A2.5 2.5 0 0 0 2 4.5zM6 3h3v2H6zm3 8v2H6v-2zm-6-1V6h2v4zm0-5v-.5A1.5 1.5 0 0 1 4.5 3H5v2zm0 6h2v2h-.5A1.5 1.5 0 0 1 3 11.5zm6.646-1.146a.5.5 0 0 1 0-.708l.647-.646H8.5a.5.5 0 0 1 0-1h1.793l-.647-.646a.5.5 0 1 1 .708-.708l1.5 1.5a.5.5 0 0 1 0 .708l-1.5 1.5a.5.5 0 0 1-.708 0");
}

</style>
