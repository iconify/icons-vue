<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="seks2d9vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:share-email" /></template>
<style>
.seks2d9vb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.5 2Q14 2 14 5.5q0 .631.114 1.149L9.236 9.494Q8.365 8.5 6.5 8.5Q3 8.5 3 12t3.5 3.5q1.855 0 2.726-.983l3.883 2.373q.072.044.153.071q.08.027.165.035q.084.009.168-.002q.085-.011.164-.04q-.009.143-.009.296v1.5q0 2.5 2.5 2.5h3.5q1.036 0 1.768-.732t.732-1.768v-1.5q0-.617-.26-1.127q.024-.144-.008-.287t-.115-.263q-.085-.123-.211-.203q-.125-.081-.272-.108q-.064-.012-.13-.012q-.648-.5-1.504-.5h-3.5q-1.195 0-1.819.571q-.183.086-.298.252q-.053.077-.086.164q-.069-.074-.156-.127l-4.008-2.449Q10 12.639 10 12q0-.631-.114-1.149l4.878-2.845Q15.635 9 17.5 9Q21 9 21 5.5T17.5 2");
}

</style>
