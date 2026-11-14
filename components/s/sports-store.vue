<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rir0cgbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sports-store" /></template>
<style>
.rir0cgbjk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.311 6.205q-.061.141-.061.295q.001 2.999 3 2.999q1.499 0 2.249-.75q.383.383.961.571q-.838.377-1.514 1.198Q5.75 11.971 5.75 14t1.196 3.482Q8.196 19 10 19q1.593 0 2.755-1.185l3.715 3.715q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-3.881-3.882q.601-1.149.601-2.588q0-2.029-1.196-3.482q-.772-.938-1.755-1.296q.408-.179.701-.472q.75.75 2.25.75t2.251-.751q.75.749 2.249.749q2.998 0 3-2.997v-.022z");
}

</style>
