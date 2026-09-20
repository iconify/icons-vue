<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="np_zrsbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speed-3-outline-rounded" /></template>
<style>
.np_zrsbol {
  fill: currentColor;
  d: path("M12.729 15.492q.596-.292.814-.93t-.172-1.196q-.927-1.364-1.876-2.698T9.608 7.97q-.218-.292-.534-.143t-.216.484q.438 1.594.878 3.173q.441 1.579.914 3.16q.192.663.835.902q.644.24 1.244-.053M5.106 19q-.294 0-.551-.122t-.353-.328q-.643-1.13-.92-2.235Q3.007 15.21 3.007 14q0-1.706.597-3.27t1.718-2.786q.164-.194.377-.191q.214.003.373.157q.16.154.168.346t-.139.369q-.988 1.07-1.541 2.446T4.006 14q0 1.025.263 2.038T5.107 18h13.792q.525-.9.813-1.925T20 14q0-1.875-.812-3.475T17.025 7.8q-1.165-.933-2.548-1.398t-2.854-.383q-.19 0-.338-.128q-.148-.127-.18-.335t.093-.36q.123-.152.312-.177q1.69-.113 3.312.42q1.622.532 2.932 1.63q1.502 1.247 2.374 3.039T21 14q0 1.4-.35 2.509t-.846 1.964q-.16.264-.395.395q-.234.132-.509.132zm6.977-4.871");
}

</style>
