<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7bbpccof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:rotate-auto-rounded" /></template>
<style>
.a7bbpccof {
  fill: currentColor;
  d: path("M20.29 15.506q-.711 1.642-1.926 2.858q-1.216 1.215-2.858 1.926T12 21q-1.79 0-3.371-.649t-2.79-1.794q-1.21-1.145-1.967-2.69t-.86-3.329q-.012-.238.131-.363t.326-.13t.36.103t.188.39q.202 3.18 2.503 5.333T12 20.025q3.35 0 5.675-2.325T20 12.025T17.675 6.35T12 4.025q-2.436 0-4.365 1.28q-1.927 1.28-2.881 3.349h2.4q.213 0 .356.143q.144.144.144.357t-.144.357t-.356.143H3.808q-.348 0-.578-.23T3 8.846V5.5q0-.213.143-.357T3.5 5t.357.143T4 5.5v2.48q1.087-2.228 3.21-3.604T12 3q1.864 0 3.506.71q1.642.711 2.857 1.927q1.216 1.215 1.926 2.857Q21 10.137 21 12t-.71 3.506M8.185 16h.946l.592-1.515q.2-.506.807-.8t2.172-.293q.53 0 .978.294q.447.293.647.799l.475 1.232q.056.142.166.213t.259.07q.24 0 .376-.187q.135-.188.049-.423l-3.235-8.204q-.036-.09-.145-.138T11.898 7q-.09 0-.165.048t-.112.138zm2.273-3.408l1.492-4.019h.1l1.53 4.02z");
}

</style>
