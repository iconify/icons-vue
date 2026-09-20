<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c_mgcedyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:reading-list-20-regular" /></template>
<style>
.c_mgcedyv {
  fill: currentColor;
  d: path("M3 6.25a1.25 1.25 0 0 1 2.29-.692a.5.5 0 1 0 .833-.555A2.25 2.25 0 1 0 4.25 8.5l.066-.004l.065.004H15.5a.5.5 0 0 0 0-1H4.381l-.065.004L4.25 7.5C3.56 7.5 3 6.94 3 6.25M8.5 5a.5.5 0 0 0 0 1h9a.5.5 0 0 0 0-1zm-3 5a.5.5 0 0 0 0 1h12a.5.5 0 0 0 0-1zM2 13a.5.5 0 0 1 .5-.5h12a.5.5 0 0 1 0 1h-12A.5.5 0 0 1 2 13m3.5 2a.5.5 0 0 0 0 1h12.003a.5.5 0 1 0 0-1z");
}

</style>
