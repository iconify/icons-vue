<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="im2_ixbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:soil-moisture-sensor" /></template>
<style>
.im2_ixbrq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.25 1.75h2.5q2.5 0 2.5 2.5v1.5q0 1.036-.732 1.768q-.35.349-.768.532v7.3q.938.172 1.749.473Q13.5 17.679 13.5 19q0 .937.3 1.75H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T1.75 20q0-.132.045-.256q1.435-3.947 6.455-4.521V8.05q-.418-.183-.768-.532q-.732-.732-.732-1.768v-1.5q0-2.5 2.5-2.5m2 13.415V8.25h-1.5v6.878q.155-.003.313-.003q.613 0 1.187.04m7.842-2.125l.286.367Q22.25 17.089 22.25 19q0 3.75-3.75 3.75T14.75 19q0-1.911 2.872-5.593l.286-.367q.045-.059.101-.107t.12-.085t.135-.06t.143-.032t.147-.004t.145.025t.137.053t.124.078q.074.058.132.132M16.25 19q0-1.309 2.25-4.275q2.25 2.966 2.25 4.275q0 2.25-2.25 2.25T16.25 19m1.25 0q0-.32.252-.856q.543.693.931 1.546q.063.139.067.292q-.116.018-.25.018q-1 0-1-1");
}

</style>
