<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvp3d6n3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:xray" /></template>
<style>
.xvp3d6n3a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.625 1.75h-9.25q-2.123 0-3.624 1.501T2.25 6.875v10.25q0 2.123 1.501 3.624t3.624 1.501h9.25q2.123 0 3.624-1.501t1.501-3.624V6.875q0-2.123-1.501-3.624T16.625 1.75M9.25 5.25q2.25 0 2.25 2.25q0 1.47-.96 1.979l3.981 3.981q.509-.96 1.979-.96q2.25 0 2.25 2.25q0 2-1.778 2.222q-.222 1.778-2.222 1.778q-2.25 0-2.25-2.25q0-1.47.96-1.979L9.479 10.54q-.509.96-1.979.96q-2.25 0-2.25-2.25q0-2 1.778-2.222Q7.25 5.25 9.25 5.25");
}

</style>
