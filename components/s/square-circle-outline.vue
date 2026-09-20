<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyn7il__y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:square-circle-outline" /></template>
<style>
.qyn7il__y {
  fill: currentColor;
  d: path("M8.192 15.808h7.616V8.192H8.192zm1-1V9.192h5.616v5.616zm-.698 5.491q-1.642-.701-2.867-1.926t-1.926-2.867T3 12t.701-3.506t1.926-2.857T8.494 3.71T12 3t3.506.71t2.857 1.927t1.926 2.857T21 12t-.71 3.506t-1.926 2.867t-2.858 1.926T12 21t-3.506-.701M12 20q3.325 0 5.663-2.328T20 12q0-3.325-2.337-5.663T12 4Q8.656 4 6.328 6.338T4 12q0 3.344 2.328 5.672T12 20m0-8");
}

</style>
