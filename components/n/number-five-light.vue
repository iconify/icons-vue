<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="p3ss13beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:number-five-light" /></template>
<style>
.p3ss13beu {
  fill: currentColor;
  d: path("M174 160a54 54 0 0 1-90 40.25a6 6 0 1 1 8-8.94a42 42 0 1 0 .8-63.31a6 6 0 0 1-9.8-5.75l15.12-75.43A6 6 0 0 1 104 42h64a6 6 0 0 1 0 12h-59.08l-11.38 56.89A54 54 0 0 1 174 160");
}

</style>
