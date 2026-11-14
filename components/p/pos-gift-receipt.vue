<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rjfany76p"/><path class="tmi63dn4l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pos-gift-receipt" /></template>
<style>
.rjfany76p {
  d: path("M13.9 21.5H2.5V11h17v2M6 11V2.5h10V11M8.5 5.5h5m-5 2.75h3m-9 6.25h9.6");
}

.tmi63dn4l {
  d: path("M18 17.5c-1.5-2.25-3.75-2.25-3.75-.75s2.25 2 3.75.75Zm0 0c1.5-2.25 3.75-2.25 3.75-.75s-2.25 2-3.75.75Zm-.75 1.75l-.5 2.25m2-2.25l.5 2.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
