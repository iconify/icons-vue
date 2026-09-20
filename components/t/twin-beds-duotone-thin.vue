<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wa-vwbbwu"/><path class="iwb9d999q"/><path class="kte_8ab6e"/><path class="czqsgdbtp"/><path class="lpfop-b2k"/><path class="c3v3u_beb"/><path class="yt443xqvj"/><path class="i55cujbki"/><path class="hrbcgxb0f"/><path class="lue0cj-so"/><path class="shmft-b2f"/><path class="q45jzkbtp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:twin-beds-duotone-thin" /></template>
<style>
.c3v3u_beb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 11V8.5h3.5V11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.czqsgdbtp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 18v-7h8v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hrbcgxb0f {
  d: path("M3 11V8.5h3.5V11");
}

.i55cujbki {
  d: path("M2 14h8");
}

.iwb9d999q {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 14h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kte_8ab6e {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 11V8.5h3.5V11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lpfop-b2k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 14h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lue0cj-so {
  d: path("M14 18v-7h8v7");
}

.q45jzkbtp {
  d: path("M15 11V8.5h3.5V11");
}

.shmft-b2f {
  d: path("M14 14h8");
}

.wa-vwbbwu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 18v-7h8v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yt443xqvj {
  d: path("M2 18v-7h8v7");
}

</style>
