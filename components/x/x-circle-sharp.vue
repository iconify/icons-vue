<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g10_s4b3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:x-circle-sharp" /></template>
<style>
.g10_s4b3d {
  fill: currentColor;
  d: path("M7.4 17.25h1.875l2.675-4.1l2.7 4.1h1.95l-3.625-5.45L16.3 6.75h-1.875l-2.45 3.8l-2.45-3.8H7.6l3.375 5.075zm.7 3.963q-1.825-.788-3.175-2.138T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22t-3.9-.788");
}

</style>
