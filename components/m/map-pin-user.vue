<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5-g1y84u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:map-pin-user" /></template>
<style>
.i5-g1y84u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.509 22.067Q3.75 15.342 3.75 9.5q0-3.417 2.416-5.834T12 1.25t5.834 2.416Q20.25 6.083 20.25 9.5q0 5.842-7.759 12.567q-.051.044-.108.078q-.058.034-.121.058q-.063.023-.129.035T12 22.25t-.133-.012t-.129-.035q-.063-.024-.121-.058t-.108-.078M12 5.5q-2.25 0-2.25 2.25T12 10t2.25-2.25T12 5.5m0 4.75q-2.558 0-3.446 2.221q-.028.069-.041.142t-.013.146t.016.146t.045.14t.071.129t.094.113t.115.092t.13.067q.069.028.142.041t.146.013t.146-.016t.14-.045t.129-.071t.113-.094t.092-.115t.067-.13Q10.458 11.75 12 11.75t2.054 1.279q.027.068.067.13t.092.115t.113.094t.129.071t.14.045t.146.016t.146-.013t.142-.041q.068-.027.13-.067t.115-.092t.094-.113t.071-.129t.045-.14t.016-.146t-.013-.146t-.041-.142Q14.558 10.25 12 10.25");
}

</style>
