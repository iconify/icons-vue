<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bnu5f798c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-cells-merge-20-regular" /></template>
<style>
.bnu5f798c {
  fill: currentColor;
  d: path("M7.354 8.854a.5.5 0 1 0-.708-.708l-1.5 1.5a.5.5 0 0 0 0 .708l1.5 1.5a.5.5 0 0 0 .708-.708l-.647-.646h6.586l-.647.646a.5.5 0 0 0 .708.708l1.5-1.5a.5.5 0 0 0 0-.708l-1.5-1.5a.5.5 0 0 0-.708.708l.647.646H6.707zM6 3a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3h8a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3zM4 7h12v6H4zm10 9H6a2 2 0 0 1-2-2h12a2 2 0 0 1-2 2m2-10H4a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2");
}

</style>
