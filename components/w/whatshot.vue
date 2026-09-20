<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqbawog_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:whatshot" /></template>
<style>
.hqbawog_q {
  fill: currentColor;
  d: path("M12 22q-2.5 0-4.587-1.1T3.95 17.95l4.1-4.1l3 2.5L16 11.4V14h2V8h-6v2h2.6l-3.65 3.65l-3-2.5L2.9 16.2q-.425-.95-.662-2.013T2 12q0-2.075.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22");
}

</style>
