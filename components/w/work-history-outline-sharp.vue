<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ror14-zfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:work-history-outline-sharp" /></template>
<style>
.ror14-zfd {
  fill: currentColor;
  d: path("M4 19V8zm-1 1V7h6V4h6v3h6v5.814q-.238-.152-.482-.265t-.518-.21V8H4v11h8.075q.056.256.12.506t.153.494zm7-13h4V5h-4zm5.165 13.836Q14 19.67 14 18t1.165-2.835T18 14t2.836 1.165T22 18t-1.164 2.836T18 22t-2.835-1.164m3.22-2.997v-2.723h-.77v3.046l2.035 2.034l.546-.546z");
}

</style>
