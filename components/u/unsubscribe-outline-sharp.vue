<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="boc2d9b5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:unsubscribe-outline-sharp" /></template>
<style>
.boc2d9b5h {
  fill: currentColor;
  d: path("M12 12.116L4 6.904v10.48q0 .27.173.443t.443.173H13q0 .275.017.503t.09.497H3V5h18v7.354q-.2-.09-.462-.154T20 12.08V6.905zM12 11l7.692-5H4.308zm4.165 9.836Q15 19.67 15 18t1.165-2.835T19 14t2.836 1.165T23 18t-1.164 2.836T19 22t-2.835-1.164m.489-2.451h4.692v-.77h-4.692zM4 18v-4.384v.057V6z");
}

</style>
