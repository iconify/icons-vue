<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcw3ep4hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-landscape-outline" /></template>
<style>
.mcw3ep4hl {
  fill: currentColor;
  d: path("M3.616 18q-.691 0-1.153-.462T2 16.384V7.54q0-.672.472-1.144t1.144-.472H6.83q.04-.373.31-.648Q7.41 5 7.789 5h1.769q.379 0 .648.275t.31.648h9.869q.67 0 1.143.472Q22 6.867 22 7.54v8.846q0 .67-.472 1.143q-.472.472-1.143.472zM21 16.384V7.54q0-.27-.173-.443t-.442-.173H3.615q-.269 0-.442.173T3 7.54v8.846q0 .269.173.442t.443.173h16.769q.269 0 .442-.173t.173-.442M3 6.923V17zm3.088 5.588q.22-.22.22-.55q0-.328-.22-.548t-.55-.22t-.549.22t-.22.549t.22.549t.55.22t.549-.22");
}

</style>
