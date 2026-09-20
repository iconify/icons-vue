<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvc7m9wml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:outpatient-med" /></template>
<style>
.cvc7m9wml {
  fill: currentColor;
  d: path("m19.34 14.814l-.707-.714l1.6-1.6h-3.867v-.98h3.861l-1.594-1.576l.733-.733L22.154 12zM2.867 5.23v-1h10v1zM6.75 17.116h2.23v-2.5h2.5v-2.231h-2.5v-2.5H6.75v2.5h-2.5v2.23h2.5zM3.48 20q-.69 0-1.152-.462t-.462-1.153v-9.77q0-.69.462-1.152T3.481 7h8.769q.69 0 1.153.463t.463 1.153v9.769q0 .69-.463 1.153T12.25 20z");
}

</style>
