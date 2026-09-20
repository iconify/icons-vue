<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttr74lbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:solo-dining-sharp" /></template>
<style>
.ttr74lbei {
  fill: currentColor;
  d: path("M9.5 8q-1.25 0-2.125-.875T6.5 5t.875-2.125T9.5 2t2.125.875T12.5 5t-.875 2.125T9.5 8M1 22v-2h2v-7.375q0-.875.713-1.625t2.062-1.25q.8-.325 1.825-.537T9.5 9q.85 0 1.913.225t1.937.575q1.275.5 1.963 1.237T16 12.625V14h-5.575l1.5 6H14l-1-4h10l-1 4h1v2z");
}

</style>
