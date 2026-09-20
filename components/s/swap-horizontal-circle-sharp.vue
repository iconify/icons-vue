<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pl5aq5bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:swap-horizontal-circle-sharp" /></template>
<style>
.pl5aq5bsf {
  fill: currentColor;
  d: path("m9 18l1.4-1.4L8.85 15H13v-2H8.85l1.55-1.6L9 10l-4 4zm6-4l4-4l-4-4l-1.4 1.4L15.15 9H11v2h4.15l-1.55 1.6zm-3 8q-2.075 0-3.9-.788t-3.175-2.137T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22");
}

</style>
