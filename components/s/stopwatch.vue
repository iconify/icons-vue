<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="fk_y4620v"/><path class="n6921tbik"/><circle class="sb0vgzbpw"/><path class="ns551uczw"/><path class="wy8ge1boa"/><circle class="rtu1-ab0q"/><circle class="su7snabqw"/><circle class="eypmbt4po"/><circle class="ey349hu4d"/><circle class="dh4wembhf"/><circle class="dj1szyx0a"/><path class="w3-my6wah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:stopwatch" /></template>
<style>
.dh4wembhf {
  cx: 9px;
  cy: 21px;
  r: 1px;
  fill: var(--svg-color--292f33, #292f33);
}

.dj1szyx0a {
  cx: 24px;
  cy: 15px;
  r: 1px;
  fill: var(--svg-color--292f33, #292f33);
}

.ey349hu4d {
  cx: 24px;
  cy: 27px;
  r: 1px;
  fill: var(--svg-color--292f33, #292f33);
}

.eypmbt4po {
  cx: 12px;
  cy: 15px;
  r: 1px;
  fill: var(--svg-color--292f33, #292f33);
}

.fk_y4620v {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M16 5h4v3h-4z");
}

.n6921tbik {
  fill: var(--svg-color--8899a6, #8899a6);
  d: path("M22 1h-8c-1.1 0-2 .9-2 2s.9 2 2 2h8c1.1 0 2-.9 2-2s-.9-2-2-2m6.184 10.507l-1.504-1.318a2.006 2.006 0 0 1-.186-2.822a2.006 2.006 0 0 1 2.822-.186l1.504 1.318c.827.725.911 1.995.186 2.822a2.006 2.006 0 0 1-2.822.186");
}

.ns551uczw {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M18 7C10.268 7 4 13.268 4 21s6.268 14 14 14s14-6.268 14-14S25.732 7 18 7m0 25c-6.065 0-11-4.935-11-11s4.935-11 11-11s11 4.935 11 11s-4.935 11-11 11");
}

.rtu1-ab0q {
  cx: 18px;
  cy: 12px;
  r: 1px;
  fill: var(--svg-color--292f33, #292f33);
}

.sb0vgzbpw {
  cx: 18px;
  cy: 21px;
  r: 11px;
  fill: var(--svg-color--f5f8fa, #f5f8fa);
}

.su7snabqw {
  cx: 18px;
  cy: 30px;
  r: 1px;
  fill: var(--svg-color--292f33, #292f33);
}

.w3-my6wah {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M12 28a.999.999 0 0 1-.707-1.707l7-7a.999.999 0 1 1 1.414 1.414l-7 7A1 1 0 0 1 12 28");
}

.wy8ge1boa {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M27 22H17a1 1 0 1 1 0-2h10a1 1 0 1 1 0 2");
}

</style>
