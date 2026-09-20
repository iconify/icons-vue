<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkzg4xfss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:x-circle-sharp" /></template>
<style>
.jkzg4xfss {
  fill: currentColor;
  d: path("M8.323 16.789h1.01l2.656-4.293l2.623 4.292h1.065L12.552 11.8l2.883-4.588h-1.01l-2.411 3.934L9.62 7.211H8.56l2.895 4.595zm.171 3.51q-1.642-.701-2.867-1.926t-1.926-2.867T3 12t.701-3.506t1.926-2.857T8.494 3.71T12 3t3.506.71t2.857 1.927t1.926 2.857T21 12t-.71 3.506t-1.926 2.867t-2.858 1.926T12 21t-3.506-.701");
}

</style>
