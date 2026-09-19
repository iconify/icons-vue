<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uju5b7b4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-optus" /></template>
<style>
.uju5b7b4t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.4 10.248c-3.705 8.978-4.845 14.956-1.069 15.676c3.777.72 7.678-8.07 7.678-8.07c-1.781 10.332-1.407 13.628-.339 19.898m4.899-10.242c5.16-.034 8.52-5.73 3.936-6.335c-4.368-.577-4.767 5.9-3.473 7.51c3.492 4.346 12.327 2.921 19.416-2.672s-.935-9.124-2.03-4.596c-.856 3.535 5.688 5.059 5.58 8.764s-4.868 4.988-5.616 1.781");
}

</style>
