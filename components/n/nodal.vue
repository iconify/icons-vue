<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":257};
const content = `<path class="d9cw9h6_p"/><path class="tsn1vebch"/><path class="roobejbva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:nodal" /></template>
<style>
.d9cw9h6_p {
  fill: var(--svg-color--138ee2, #138ee2);
  d: path("M192.083 0L127.84 43.18l.233 1.398l62.406 41.603l1.604.04l.803-1.359l.155-82.975z");
}

.roobejbva {
  fill: var(--svg-color--00e1ff, #00e1ff);
  d: path("M0 42.944v170.778l64.333 42.61v-85.221l127.75 85.555l63.584-42.611L64.915.999z");
}

.tsn1vebch {
  fill: var(--svg-color--00bdff, #00bdff);
  d: path("m62.92 174.229l-.211 78.21l1.624 3.894l63.925-42.408l-.443-2.282l-58.764-39.317l-4.718-1.215zM192.083 0v86.221L64.915.998l-.79 3.538L251.05 212.488l4.95 1.816V42.777z");
}

</style>
