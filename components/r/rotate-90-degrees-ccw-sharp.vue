<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyc__obwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:rotate-90-degrees-ccw-sharp" /></template>
<style>
.dyc__obwn {
  fill: currentColor;
  d: path("M12.789 21q-1.083 0-2.116-.292q-1.032-.292-1.954-.839l.72-.719q.775.425 1.625.638t1.725.212q2.925 0 4.962-2.037T19.789 13T17.75 8.037T12.789 6h-1.304l2.011 2.011l-.708.797L9.481 5.5l3.308-3.308l.707.797L11.485 5h1.304q3.327 0 5.663 2.337T20.788 13q0 1.664-.626 3.118t-1.713 2.543t-2.542 1.713t-3.118.626m-6-3.423L2.212 13l4.577-4.577L11.366 13z");
}

</style>
