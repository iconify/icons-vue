<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8mv83bwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mouse-sharp" /></template>
<style>
.h8mv83bwb {
  fill: currentColor;
  d: path("M12.004 21q-2.506 0-4.255-1.747Q6 17.508 6 15v-4.923h12V15q0 2.507-1.745 4.254T12.004 21M6 9.077q0-2.356 1.575-4.078T11.5 3.094v5.983zm6.5 0V3.094q2.35.183 3.925 1.905T18 9.077z");
}

</style>
