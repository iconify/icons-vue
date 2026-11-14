<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="np_gi5ipv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:treat-jar" /></template>
<style>
.np_gi5ipv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 2h13q2.75 0 2.75 2.75q0 1.658-1 2.317V18.5q0 1.346-.952 2.298T17 21.75H7q-1.346 0-2.298-.952T3.75 18.5V7.067q-1-.659-1-2.317q0-1.139.805-1.945Q4.361 2 5.5 2m-.25 5.494V18.5q0 .725.513 1.237q.512.513 1.237.513h10q.725 0 1.237-.513q.513-.512.513-1.237V7.494q-.122.006-.25.006h-13q-.128 0-.25-.006m4.846 9.485q.771-.701.742-1.479h2.324q-.029.778.742 1.479q1.346 1.225 2.692 0q1.346-1.224.254-2.679q-.032-.043-.07-.08q-.219-.22 0-.44q.038-.037.07-.08q1.092-1.455-.254-2.679q-1.346-1.225-2.692 0q-.771.701-.742 1.479h-2.324q.029-.778-.742-1.479q-1.346-1.225-2.692 0q-1.346 1.224-.254 2.679q.032.043.07.08q.219.22 0 .44q-.038.037-.07.08q-1.092 1.455.254 2.679q1.346 1.225 2.692 0");
}

</style>
