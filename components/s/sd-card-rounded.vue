<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmf3anb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sd-card-rounded" /></template>
<style>
.lmf3anb2c {
  fill: currentColor;
  d: path("M6.616 21q-.691 0-1.153-.462T5 19.385V9.095q0-.332.13-.633t.349-.518L9.944 3.48q.217-.218.518-.348T11.094 3h6.29q.691 0 1.153.462T19 4.615v14.77q0 .69-.463 1.152T17.385 21zm3.818-10.375q.143-.143.143-.356V7.846q0-.212-.144-.356t-.357-.144t-.356.144t-.143.356v2.423q0 .213.144.356q.144.144.357.144t.356-.144m2.807 0q.144-.143.144-.356V7.846q0-.212-.144-.356t-.357-.144t-.356.144t-.144.356v2.423q0 .213.145.356t.356.144t.356-.144m2.808 0q.143-.143.143-.356V7.846q0-.212-.144-.356q-.143-.144-.356-.144t-.357.144t-.143.356v2.423q0 .213.144.356t.357.144t.356-.144");
}

</style>
