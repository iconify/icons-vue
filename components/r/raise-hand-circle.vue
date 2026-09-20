<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="vdoyxmblk"/><path class="j7e2n10ck"/><path class="e_f4mqb0l"/><path class="hdxpysbbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:raise-hand-circle" /></template>
<style>
.e_f4mqb0l {
  d: path("M10.5 15a1 1 0 0 1 1-1H14a6 6 0 0 1 6 6v2a1 1 0 1 1-2 0v-2a4 4 0 0 0-4-4h-2.5a1 1 0 0 1-1-1m-.5 3.5a1 1 0 0 1 1 1V22a1 1 0 1 1-2 0v-2.5a1 1 0 0 1 1-1");
}

.hdxpysbbn {
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.j7e2n10ck {
  d: path("M5 7a2.5 2.5 0 0 1 5 0v3.272c0 .883.31 1.737.874 2.415l1.394 1.673a1 1 0 1 1-1.536 1.28l-1.394-1.673A5.77 5.77 0 0 1 8 10.272V7a.5.5 0 0 0-1 0v3.75a4 4 0 0 0 .47 1.882l3.412 6.397a1 1 0 0 1-1.764.942l-3.412-6.398A6 6 0 0 1 5 10.75z");
}

.n1lsf0bnc {
  fill: currentColor;
  fill-rule: evenodd;
}

.vdoyxmblk {
  d: path("M14.5 9a2.5 2.5 0 1 0 0 5a2.5 2.5 0 0 0 0-5M10 11.5a4.5 4.5 0 1 1 9 0a4.5 4.5 0 0 1-9 0");
}

</style>
