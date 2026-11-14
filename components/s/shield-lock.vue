<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvo-atvln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:shield-lock" /></template>
<style>
.bvo-atvln {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m12.258 2.046l7.5 2.75q.108.04.2.11q.091.07.157.165q.066.094.1.204q.035.11.035.225v6q0 7.276-7.973 10.447Q12.144 22 12 22t-.277-.053Q3.75 18.776 3.75 11.5v-6q0-.115.035-.225q.034-.11.1-.204q.066-.095.157-.165q.092-.07.2-.11l7.5-2.75Q11.867 2 12 2t.258.046M11 10.25h2v-.5q0-.414-.293-.707T12 8.75q-1 0-1 1zm3.5.328V9.75q0-1.036-.732-1.768T12 7.25q-2.5 0-2.5 2.5v.714q-1.25.518-1.25 2.286v1.5q0 2.5 2.5 2.5h2.5q1.036 0 1.768-.732t.732-1.768v-1.5q0-1.036-.732-1.768q-.243-.242-.518-.404");
}

</style>
