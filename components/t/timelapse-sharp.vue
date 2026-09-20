<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmjdieuzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:timelapse-sharp" /></template>
<style>
.gmjdieuzf {
  fill: currentColor;
  d: path("M12 18q2.5 0 4.25-1.75T18 12t-1.75-4.25T12 6v6l-4.25 4.25q.875.825 1.963 1.288T12 18m0 4q-2.075 0-3.9-.788t-3.175-2.137T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22");
}

</style>
