<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-vz1jb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:satellite-dish-off" /></template>
<style>
.o-vz1jb2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.774 11.726L4.5 15q.196.147.402.281q.205.134.419.255q.214.12.435.226t.449.198t.461.168t.471.137t.479.106t.484.075t.489.043t.49.011q.246-.003.49-.022q.245-.018.488-.053q.243-.034.483-.085q.24-.05.476-.116q.237-.066.468-.147q.232-.082.457-.178m3.966-3.976q.095-.226.176-.457t.146-.467t.115-.475q.049-.24.083-.482q.034-.243.052-.487q.019-.244.021-.488q.002-.245-.012-.489q-.014-.245-.043-.488q-.03-.243-.076-.483q-.045-.241-.106-.478t-.137-.469q-.077-.233-.168-.46t-.197-.447q-.106-.221-.227-.434q-.12-.213-.253-.418q-.134-.205-.281-.401l-3.266 3.266M9.75 17.25v4.25m-3.25 0H13m-9.5-18l17 17");
}

</style>
