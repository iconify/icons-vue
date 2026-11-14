<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvbmunbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:underwriting-declined" /></template>
<style>
.pvbmunbbp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m12.258 2.046l7.5 2.75q.108.04.2.11q.091.07.157.165q.066.094.1.204q.035.11.035.225v6q0 7.276-7.973 10.447Q12.144 22 12 22t-.277-.053Q3.75 18.776 3.75 11.5v-6q0-.115.035-.225q.034-.11.1-.204q.066-.095.157-.165q.092-.07.2-.11l7.5-2.75Q11.867 2 12 2t.258.046");
}

</style>
