<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0l-r0bbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:replica-shirt" /></template>
<style>
.c0l-r0bbc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15 2.25H9q-.089 0-.175.021q-.086.02-.166.061q-.079.04-.146.098q-.068.057-.12.129q-.351.052-.729.224L3.889 4.499q-1.049.477-1.275 1.607l-.578 2.891q-.407 2.034 1.588 2.604l1.082.309q.544.156.544.721V19.5q0 2.25 2.25 2.25h9q2.25 0 2.25-2.25v-6.869q0-.565.544-.721l1.082-.309q1.995-.57 1.588-2.604l-.578-2.891q-.226-1.13-1.275-1.607l-3.775-1.716q-.378-.172-.729-.224q-.052-.072-.12-.129q-.067-.058-.146-.098q-.08-.041-.166-.061q-.086-.021-.175-.021m-1.631 1.5l-.8.933q-.224.262-.569.262t-.57-.262l-.799-.933z");
}

</style>
