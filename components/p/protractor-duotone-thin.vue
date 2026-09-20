<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u0jypcc9y"/><path class="ttx6bbv4v"/><path class="z4137abip"/><path class="dh-2h3b4q"/><path class="srzgk7jml"/><path class="ic_pehd5a"/><path class="on0zajbot"/><path class="uzmclv6tb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:protractor-duotone-thin" /></template>
<style>
.dh-2h3b4q {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 8v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ic_pehd5a {
  d: path("M3 17h18");
}

.on0zajbot {
  d: path("M7 17a5 5 0 0 1 10 0");
}

.srzgk7jml {
  d: path("M3 17a9 9 0 0 1 18 0");
}

.ttx6bbv4v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 17h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u0jypcc9y {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 17a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uzmclv6tb {
  d: path("M12 8v3");
}

.z4137abip {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 17a5 5 0 0 1 10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
