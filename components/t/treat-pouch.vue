<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcqikcbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:treat-pouch" /></template>
<style>
.fcqikcbpx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.914 6.7q5.336 3.614 5.336 9.8q0 5.75-9.25 5.75T2.75 16.5q0-6.186 5.336-9.8L6.798 3.263q-.053-.139-.048-.288q.005-.15.067-.285q.062-.136.171-.238t.249-.154q.127-.048.263-.048h9q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .136-.048.263zM9.52 6.25h4.96l.938-2.5H8.582zm1.568 7q.029-.778-.742-1.479q-1.346-1.225-2.692 0q-1.245 1.132-.404 2.462v1.534q-.841 1.33.404 2.462q1.346 1.225 2.692 0q.771-.701.742-1.479h1.824q-.029.778.742 1.479q1.346 1.225 2.692 0q1.245-1.132.404-2.462v-1.534q.841-1.33-.404-2.462q-1.346-1.225-2.692 0q-.771.701-.742 1.479z");
}

</style>
