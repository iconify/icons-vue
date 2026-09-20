<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw8-skbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:water-lock-outline-rounded" /></template>
<style>
.iw8-skbiq {
  fill: currentColor;
  d: path("M6 20V10v9.385v-.01zM9 9h6V7q0-1.25-.875-2.125T12 4t-2.125.875T9 7zM6.616 21q-.672 0-1.144-.472T5 19.385v-8.77q0-.67.472-1.143Q5.944 9 6.616 9H8V7q0-1.671 1.165-2.835Q10.329 3 12 3t2.836 1.165T16 7v2h1.385q.67 0 1.143.472q.472.472.472 1.144v2.826q0 .25-.159.366q-.158.115-.341.115t-.341-.125t-.159-.375v-2.807q0-.27-.173-.443T17.385 10H6.615q-.269 0-.442.173T6 10.616v8.769q0 .269.173.442t.443.173h7.423q.25 0 .375.159q.125.158.125.341t-.125.341t-.375.159zm11.903 0q-.838 0-1.419-.58T16.52 19q0-.385.136-.73t.379-.618l1.03-1.142q.187-.212.454-.212t.454.212l1.03 1.142q.243.273.38.618t.136.73q0 .839-.58 1.42t-1.42.58m-5.453-4.934q.434-.433.434-1.066t-.434-1.066T12 13.5t-1.066.434Q10.5 14.367 10.5 15t.434 1.066q.433.434 1.066.434t1.066-.434");
}

</style>
