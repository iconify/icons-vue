<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4alf7b0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:wedding-invitation" /></template>
<style>
.p4alf7b0x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.745 3.495Q5.5 4.74 5.5 6.5q0 1.584 1.007 2.75H6q-.37 0-.718.055q.082.033.154.085L12 14.078l6.564-4.688q.072-.052.154-.085Q18.37 9.25 18 9.25h-.507Q18.5 8.084 18.5 6.5q0-1.76-1.245-3.005T14.25 2.25q-1.256 0-2.25.634q-.994-.634-2.25-.634q-1.76 0-3.005 1.245m12.853 6.053l.012.016q.043.06.074.128q.03.067.047.139q.016.072.019.146q.002.073-.01.146t-.038.142q-.027.069-.066.132t-.089.117q-.051.053-.111.096l-7 5q-.047.034-.1.06q-.052.026-.107.044q-.056.018-.113.027q-.058.009-.116.009t-.116-.009t-.113-.027t-.107-.044t-.1-.06l-7-5q-.121-.086-.2-.213t-.104-.274q-.024-.147.009-.292q.034-.146.121-.267l.012-.016q-.771.311-1.407.947Q1.75 11.74 1.75 13.5v4q0 1.76 1.245 3.005T6 21.75h12q1.76 0 3.005-1.245T22.25 17.5v-4q0-1.76-1.245-3.005q-.636-.636-1.407-.947");
}

</style>
