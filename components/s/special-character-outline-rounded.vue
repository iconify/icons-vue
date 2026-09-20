<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="giprnlbfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:special-character-outline-rounded" /></template>
<style>
.giprnlbfn {
  fill: currentColor;
  d: path("M7.83 6.716Q6.117 8.43 6.117 10.885q0 1.844 1.036 3.351t2.77 2.15q.387.166.637.476q.249.311.249.711v1.215q0 .51-.351.861t-.86.351H5q-.413 0-.707-.293T4 19t.293-.707T5 18h3.616q-2.081-.99-3.291-2.904t-1.21-4.211q0-3.281 2.302-5.583T12 3t5.583 2.302t2.302 5.583q0 2.298-1.21 4.211T15.385 18H19q.414 0 .707.293T20 19t-.293.707T19 20h-4.596q-.51 0-.86-.351t-.352-.86v-1.216q0-.4.25-.71q.249-.311.637-.476q1.733-.643 2.769-2.15t1.037-3.352q0-2.454-1.716-4.17T12 5T7.83 6.716");
}

</style>
