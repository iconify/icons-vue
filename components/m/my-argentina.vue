<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ep7kif79l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-argentina" /></template>
<style>
.ep7kif79l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.87 36.017c-.605-.726-.472-1.935.67-1.935h12.44c1.141 0 1.274 1.209.669 1.935l-5.197 6.274c-.453.544-.756 1.209-1.693 1.209c-.941 0-1.243-.665-1.697-1.21zm22.132-29.56a1.965 1.965 0 0 1-1.972 1.958a1.965 1.965 0 0 1-1.97-1.957A1.965 1.965 0 0 1 37.03 4.5a1.965 1.965 0 0 1 1.973 1.958Zm-1.972 6.857v14.83m-16.766-9.23c0-3.09 2.52-5.593 5.631-5.593c3.107 0 5.632 2.502 5.632 5.594v9.237M8.997 13.314v14.83m0-9.233c0-3.092 2.521-5.594 5.632-5.594s5.631 2.502 5.631 5.594v9.237");
}

</style>
