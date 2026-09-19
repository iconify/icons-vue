<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gvim0vlza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sanskrit-basics" /></template>
<style>
.gvim0vlza {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.775 5.5h28.45m-7.107 0v11.382c-.24 8.264-9.96 9.96-17.079 0L33.961 42.5");
}

</style>
