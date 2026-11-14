<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="srg1uq9pl"/><path class="yjkwfv9oj"/><path class="cgk9heboa"/><path class="ic3-py20j"/><path class="mghpytq_j"/><path class="tzwrcu4yi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pos-price-check" /></template>
<style>
.cgk9heboa {
  fill: currentColor;
  d: path("M10 4za1 1 0 0 1 1 1v11a1 1 0 0 1-1 1a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ic3-py20j {
  d: path("M13.5 4v10.7");
}

.mghpytq_j {
  fill: currentColor;
  d: path("M15.505 12.834q-.005-.042-.005-.084v-8q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T16.25 4t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v7.739");
}

.srg1uq9pl {
  fill: currentColor;
  d: path("M3.75 4za.75.75 0 0 1 .75.75v11.5a.75.75 0 0 1-.75.75a.75.75 0 0 1-.75-.75V4.75A.75.75 0 0 1 3.75 4");
}

.tzwrcu4yi {
  d: path("M2.5 9.5h19m-6.333 7.491l1.137-1.25a1.5 1.5 0 0 1 1.11-.491h2.836a1.5 1.5 0 0 1 1.5 1.5v2.5a1.5 1.5 0 0 1-1.5 1.5h-2.836a1.5 1.5 0 0 1-1.11-.491l-1.137-1.25a1.5 1.5 0 0 1 0-2.018M17 18h.01");
}

.yjkwfv9oj {
  d: path("M7 4v13");
}

</style>
