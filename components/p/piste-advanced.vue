<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umjs6yoqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:piste-advanced" /></template>
<style>
.umjs6yoqd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m20.174 9.614l-5.788-5.788Q12 1.44 9.614 3.826L3.826 9.614q-2.386 2.386 0 4.772l5.788 5.788q2.386 2.386 4.772 0l5.788-5.788q2.386-2.386 0-4.772m-6.583-1.333l2.128 2.128q.66.659.66 1.591t-.66 1.591l-2.128 2.128q-.659.66-1.591.66t-1.591-.66l-2.128-2.128q-.66-.659-.66-1.591t.66-1.591l2.128-2.128q.659-.66 1.591-.66t1.591.66");
}

</style>
