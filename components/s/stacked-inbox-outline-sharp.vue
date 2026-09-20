<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dq5os3blx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stacked-inbox-outline-sharp" /></template>
<style>
.dq5os3blx {
  fill: currentColor;
  d: path("M5 17V3h18v14zm2-5v3h14v-3h-3.55q-.525.9-1.425 1.45T14 14t-2.025-.55T10.55 12zm7 0q.825 0 1.413-.587T16 10h5V5H7v5h5q0 .825.588 1.413T14 12m5 9H1V7h2v12h16zM7 15h14z");
}

</style>
