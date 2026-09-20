<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h52pcjajq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:solo-dining-outline-sharp" /></template>
<style>
.h52pcjajq {
  fill: currentColor;
  d: path("M1 22v-2h2v-7.375q0-.875.713-1.625t2.062-1.25q.8-.325 1.825-.537T9.5 9q.85 0 1.913.225t1.937.575q1.275.5 1.963 1.237T16 12.625V14h-2v-1.375q-.05-.2-.437-.462t-.938-.513q-.725-.3-1.525-.475T9.5 11t-1.6.175t-1.525.475q-.55.25-.937.525T5 12.65V20h9l-1-4h10l-1 4h1v2zm19.45-4h-4.9l.5 2h3.9zM9.5 8q-1.25 0-2.125-.875T6.5 5t.875-2.125T9.5 2t2.125.875T12.5 5t-.875 2.125T9.5 8m.713-2.287Q10.5 5.425 10.5 5t-.288-.712T9.5 4t-.712.288T8.5 5t.288.713T9.5 6t.713-.288M18 20");
}

</style>
