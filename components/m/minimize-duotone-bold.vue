<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="s_ze6rbor"/><path class="pi_2vs7jd"/><path class="e3t5-zh5a"/><path class="k0u1xubfi"/><path class="gsqbmignj"/><path class="dpjjh6qnb"/><path class="ya5oksyke"/><path class="uiel3fblr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:minimize-duotone-bold" /></template>
<style>
.dpjjh6qnb {
  d: path("M15 3v6h6");
}

.e3t5-zh5a {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 15h-6v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gsqbmignj {
  d: path("M9 3v6H3");
}

.k0u1xubfi {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 21v-6H3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pi_2vs7jd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 3v6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s_ze6rbor {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 3v6H3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uiel3fblr {
  d: path("M9 21v-6H3");
}

.ya5oksyke {
  d: path("M21 15h-6v6");
}

</style>
