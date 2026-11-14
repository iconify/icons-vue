<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2880qb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:triage-black" /></template>
<style>
.c2880qb4t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.571 6.818Q12.32 6.75 12 6.75q-1.499.001-1.499 1.5T12 9.75q1.499-.001 1.499-1.5q0-.634-.268-1q-.223-.006-.406-.132q-.168-.115-.254-.3m2.44-1.556l2.93 2.131q.072.053.129.12q.058.068.098.147q.041.079.061.165q.021.086.021.175v11.5q0 2.75-2.75 2.75h-7q-1.136 0-1.943-.807T5.75 19.5V8q0-.089.021-.175q.02-.086.061-.165t.098-.147q.057-.067.129-.12l5.5-4q.048-.034.1-.061t.109-.045q.056-.019.115-.028q.058-.009.117-.009t.117.009t.115.028q.056.018.109.045q.052.027.1.061l1.356.987l1.585-2.305q.084-.123.21-.204q.125-.081.271-.108q.147-.028.293.003t.269.116q.061.042.112.095t.092.115q.04.062.068.13q.027.069.04.141q.014.073.013.147t-.016.146t-.045.14q-.029.068-.071.129z");
}

</style>
