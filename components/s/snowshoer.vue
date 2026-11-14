<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqt0-qbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:snowshoer" /></template>
<style>
.yqt0-qbyv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 7.196Q9 6.848 9 4.25q0-3 3-3t3 3q0 2.598-2.25 2.946v1.659l3.675 2.527q.061.042.112.095t.092.115q.04.062.068.13q.027.069.04.141q.014.073.013.147t-.016.146t-.045.14q-.029.068-.071.129q-.084.123-.21.204q-.125.081-.271.108q-.147.028-.293-.003t-.269-.116l-2.825-1.942V12.2l4.826 5.055q1.514.051 2.643.578q1.531.714 1.531 1.917t-1.531 1.917q-1.249.583-2.969.583q-4.5 0-4.5-2.5q0-1.989 2.847-2.395L12 13.586l-3.638 3.812q.736.145 1.357.435q1.531.714 1.531 1.917t-1.531 1.917q-1.249.583-2.969.583q-4.5 0-4.5-2.5q0-2.408 4.176-2.497L11.25 12.2v-1.524l-2.825 1.942q-.061.042-.129.071t-.14.045t-.146.016t-.147-.013t-.141-.04t-.13-.068t-.115-.092t-.095-.112q-.085-.123-.116-.269t-.003-.293t.108-.271q.081-.126.204-.21l3.675-2.527z");
}

</style>
