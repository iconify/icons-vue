<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unbkf6b7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:no-food-rounded" /></template>
<style>
.unbkf6b7c {
  fill: currentColor;
  d: path("M19.775 22.575L12.175 15h-9.95q-.475 0-.788-.363t-.212-.837q.25-1.275.975-2.187t1.725-1.5t2.188-.85T8.5 9q.125 0 .275.013t.275.012v2.825L1.375 4.2q-.3-.3-.3-.712t.3-.713t.713-.3t.712.3l18.4 18.4q.3.3.3.7t-.3.7t-.712.3t-.713-.3M2 19q-.425 0-.712-.288T1 18t.288-.712T2 17h13q.425 0 .713.288T16 18t-.288.713T15 19zm0 4q-.425 0-.712-.288T1 22t.288-.712T2 21h13q.425 0 .713.288T16 22t-.288.713T15 23zm18.625-5.45q-.275-.05-.5-.275L11.95 9.1q-.25-.25-.387-.537t-.188-.638l-.225-1.8q-.05-.45.238-.787T12.125 5H16V2q0-.425.288-.712T17 1t.713.288T18 2v3h3.9q.45 0 .75.325t.25.775l-1.075 10.55q-.05.325-.213.538t-.437.312t-.55.05");
}

</style>
