<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v6a6cl77s"/><path class="kxha5zv0a"/><path class="nltnw0s5u"/><path class="lq7krbcst"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:school-nurse" /></template>
<style>
.kxha5zv0a {
  fill: currentColor;
  d: path("m6.75 4.75l1-2.5h5.5l1 2.5q-3.75-1.125-7.5 0Z");
}

.lq7krbcst {
  d: path("M16.5 18.5H20v2h-3.5Z");
}

.nltnw0s5u {
  d: path("M14.75 15.5h7v6.25h-7Zm1.5 0c0-1.5 1.5-1.5 1.5 0m1 0c0-1.5 1.5-1.5 1.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v6a6cl77s {
  d: path("M11.972 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5q.758 0 1.468.093M6.573 7.761q.033.17.08.336q.048.166.109.327t.136.316t.164.304t.188.288q.101.141.213.272q.113.131.236.251q.123.121.256.231t.275.208q.142.097.292.183t.307.157t.319.131q.162.058.329.102t.337.074t.342.044q.171.015.344.015q.174 0 .348-.015q.173-.015.345-.045q.171-.031.34-.076q.168-.045.332-.104q.163-.059.321-.133q.158-.073.309-.16t.294-.187t.277-.211t.257-.235t.235-.256q.113-.133.213-.275t.188-.294q.087-.15.161-.308q.074-.157.134-.321q.06-.163.106-.332q.046-.168.077-.339");
}

</style>
