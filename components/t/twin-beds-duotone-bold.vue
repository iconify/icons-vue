<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wmv2-77kt"/><path class="iy_1f_g-m"/><path class="unyd1doyx"/><path class="d-2hrr-me"/><path class="t1k-nry8t"/><path class="bgwq5j27t"/><path class="yt443xqvj"/><path class="i55cujbki"/><path class="hrbcgxb0f"/><path class="lue0cj-so"/><path class="shmft-b2f"/><path class="q45jzkbtp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:twin-beds-duotone-bold" /></template>
<style>
.bgwq5j27t {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 11V8.5h3.5V11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d-2hrr-me {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 18v-7h8v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hrbcgxb0f {
  d: path("M3 11V8.5h3.5V11");
}

.i55cujbki {
  d: path("M2 14h8");
}

.iy_1f_g-m {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 14h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lue0cj-so {
  d: path("M14 18v-7h8v7");
}

.q45jzkbtp {
  d: path("M15 11V8.5h3.5V11");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.shmft-b2f {
  d: path("M14 14h8");
}

.t1k-nry8t {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 14h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.unyd1doyx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 11V8.5h3.5V11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wmv2-77kt {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 18v-7h8v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yt443xqvj {
  d: path("M2 18v-7h8v7");
}

</style>
