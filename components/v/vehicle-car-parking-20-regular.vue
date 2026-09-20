<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r1dh-xb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:vehicle-car-parking-20-regular" /></template>
<style>
.r1dh-xb6h {
  fill: currentColor;
  d: path("M14 1.5a.5.5 0 0 1 .5-.5h4a.5.5 0 0 1 .5.5v5a.5.5 0 0 1-.5.5H17v11.5a.5.5 0 0 1-1 0V7h-1.5a.5.5 0 0 1-.5-.5zM13 3H6.14a2.5 2.5 0 0 0-2.452 2.01L3.49 6h-.74a.75.75 0 0 0 0 1.5h.44l-.111.56A1.5 1.5 0 0 0 2 9.5v5A1.5 1.5 0 0 0 3.5 16H4v1a1 1 0 1 0 2 0v-1h8v1a1 1 0 0 0 1 1v-3H3.5a.5.5 0 0 1-.5-.5v-5a.5.5 0 0 1 .5-.5H15V8H4.11l.559-2.794A1.5 1.5 0 0 1 6.139 4H13zm2 9a1 1 0 1 0-2 0a1 1 0 0 0 2 0m-8 0a1 1 0 1 0-2 0a1 1 0 0 0 2 0");
}

</style>
