<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srndgdtay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:text-fields-alt-rounded" /></template>
<style>
.srndgdtay {
  fill: currentColor;
  d: path("M2.616 19h18.769q.252 0 .433.182t.182.434t-.182.433t-.433.182H2.615q-.251 0-.433-.182T2 19.616t.182-.434t.434-.182M19 16.558V4.442q0-.19.126-.316T19.442 4t.317.126t.126.316v12.116q0 .19-.126.316t-.317.126t-.316-.126t-.126-.316M7.335 13.38l-1.333 3.298q-.067.158-.191.24T5.51 17q-.287 0-.442-.228q-.154-.228-.05-.49l4.9-11.994q.047-.119.155-.204T10.319 4h.362q.144 0 .249.084q.104.085.153.204l4.886 11.943q.104.28-.07.525t-.46.244q-.178 0-.314-.094t-.204-.271L13.62 13.38zm.373-.981h5.527l-2.743-6.8h-.023z");
}

</style>
