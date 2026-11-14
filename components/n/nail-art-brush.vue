<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck-7cmbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:nail-art-brush" /></template>
<style>
.ck-7cmbrt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.479 7.776q-.667.445-.831 1.191q-.796 0-1.592.796L3.399 15.42q-1.591 1.591 0 3.181t3.181 0l5.657-5.657q.796-.796.796-1.592q.746-.164 1.191-.831l1.289-1.933q.69-1.033-.189-1.912t-1.912-.189zm7.607.255Q21.25 10.737 21.25 12q0 2.75-2.75 2.75T15.75 12q0-1.263 2.164-3.969q.094-.116.224-.188q.131-.072.279-.088q.148-.017.292.025q.143.041.26.134q.065.052.117.117");
}

</style>
