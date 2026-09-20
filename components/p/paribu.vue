<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="neh2ubb2b"/><path class="gsm-rbcnl"/><path class="akuo363kb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:paribu" /></template>
<style>
.akuo363kb {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.336 11.072q-.153.279-.405.432q-.253.153-.585.206a4.3 4.3 0 0 1-.69.053h-1.62V8.92h1.62q.358 0 .69.053t.585.206t.405.432t.152.73q0 .453-.152.73m1.645-1.784a2.45 2.45 0 0 0-.533-.906a2.7 2.7 0 0 0-.95-.64q-.582-.241-1.414-.242H7.85v1.422h1.29v2.841H7.85v1.422h1.29V16.5h1.895v-3.315h2.048q.831 0 1.414-.242q.584-.242.95-.64q.366-.396.533-.911t.168-1.049q0-.547-.168-1.055");
}

.ft5dv1b6b {
  fill: none;
}

.gsm-rbcnl {
  fill: var(--svg-color--8fa63c, #8fa63c);
  d: path("m3 3l18 18V3z");
}

.neh2ubb2b {
  fill: var(--svg-color--618138, #618138);
  d: path("M3 21h18L3 3z");
}

</style>
