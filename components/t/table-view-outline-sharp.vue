<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwy2_h9gz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:table-view-outline-sharp" /></template>
<style>
.zwy2_h9gz {
  fill: currentColor;
  d: path("M6 22V6h16v16zm2-2h5v-3H8zm7 0h5v-3h-5zM2 18V2h16v2H4v14zm6-3h5v-3H8zm7 0h5v-3h-5zm-7-5h12V8H8z");
}

</style>
