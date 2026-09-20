<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<ellipse transform="rotate(-14.999 5.05 17.456)" class="zy00p6pyk"/><ellipse transform="rotate(-75.001 31.05 17.455)" class="w43bh0byz"/><path class="r2huijbev"/><path class="m6lo2bcmr"/><ellipse class="qh4mx1bva"/><ellipse class="x_yy6e8um"/><path class="z-_6ui20i"/><circle class="p4tqjqb8b"/><circle class="mrqvwkbos"/><path class="bg2e4_b9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:monkey-face" /></template>
<style>
.bg2e4_b9o {
  fill: var(--svg-color--bf6952, #bf6952);
  d: path("M22.66.175s-5.455-1.091-7.636 2.182s4.364 1.091 4.364 1.091S20.478.175 22.66.175");
}

.m6lo2bcmr {
  fill: var(--svg-color--d79e84, #d79e84);
  d: path("M30 16.042C30 12.153 26.825 9 22.909 9A7.1 7.1 0 0 0 18 10.968A7.1 7.1 0 0 0 13.091 9C9.175 9 6 12.153 6 16.042c0 2.359 1.172 4.441 2.965 5.719a10.7 10.7 0 0 0-.783 4.031C8.182 31.476 12.578 35 18 35s9.818-3.524 9.818-9.208c0-1.431-.28-2.793-.783-4.031C28.828 20.483 30 18.4 30 16.042");
}

.mrqvwkbos {
  cx: 19.75px;
  cy: 23px;
  r: 1px;
  fill: var(--svg-color--642116, #642116);
}

.p4tqjqb8b {
  cx: 16.25px;
  cy: 23px;
  r: 1px;
  fill: var(--svg-color--642116, #642116);
}

.qh4mx1bva {
  cx: 13px;
  cy: 17px;
  fill: var(--svg-color--292f33, #292f33);
  rx: 2.25px;
  ry: 3.25px;
}

.r2huijbev {
  fill: var(--svg-color--bf6952, #bf6952);
  d: path("M19.018 36h-2.036C10.264 36 3.75 30.848 3.75 23.636c0-4.121 1.527-6.182 1.527-6.182s-.509-2.061-.509-4.121C4.768 7.152 11.282 2 18 2s13.232 6.182 13.232 11.333c0 2.061-.509 4.121-.509 4.121s1.527 2.061 1.527 6.182C32.25 30.848 25.736 36 19.018 36");
}

.w43bh0byz {
  cx: 31.05px;
  cy: 17.455px;
  fill: var(--svg-color--d79e84, #d79e84);
  rx: 5.455px;
  ry: 3.818px;
}

.x_yy6e8um {
  cx: 23px;
  cy: 17px;
  fill: var(--svg-color--292f33, #292f33);
  rx: 2.25px;
  ry: 3.25px;
}

.z-_6ui20i {
  fill: var(--svg-color--642116, #642116);
  d: path("M18 32.727c2.838 0 5.254-1.505 6.162-3.61a1.32 1.32 0 0 0-1.21-1.844h-9.904a1.32 1.32 0 0 0-1.21 1.844c.908 2.105 3.324 3.61 6.162 3.61");
}

.zy00p6pyk {
  cx: 5.05px;
  cy: 17.455px;
  fill: var(--svg-color--d79e84, #d79e84);
  rx: 3.818px;
  ry: 5.455px;
}

</style>
