<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wakpdab1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:share-lock" /></template>
<style>
.wakpdab1m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.5 2Q14 2 14 5.5q0 .631.114 1.149L9.236 9.494Q8.365 8.5 6.5 8.5Q3 8.5 3 12t3.5 3.5q1.855 0 2.726-.983l3.883 2.373q.063.038.132.064q.07.025.143.037t.146.008q.074-.003.146-.02t.139-.048t.127-.075q.059-.043.109-.098q.05-.054.089-.117q.078-.127.101-.275q.023-.147-.012-.292t-.123-.266t-.215-.198l-4.008-2.449Q10 12.639 10 12q0-.631-.114-1.149l4.878-2.845Q15.635 9 17.5 9Q21 9 21 5.5T17.5 2M17 15.75h2v-.5q0-.414-.293-.707T18 14.25q-1 0-1 1zm3.5.328q.275.162.518.404q.732.732.732 1.768v1q0 1.036-.732 1.768t-1.768.732h-2.5q-1.036 0-1.768-.732t-.732-1.768v-1q0-1.768 1.25-2.286v-.714q0-2.5 2.5-2.5q1.036 0 1.768.732t.732 1.768z");
}

</style>
