<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vlqezoe9y"/><path class="fl0wk1jmb"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:package-outdated" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.fl0wk1jmb {
  d: path("m2.5 6.5l8.5 4l8.5-4m-8.5 4v9m3.75-1.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vlqezoe9y {
  d: path("m12.061 19l-.316.149q-.175.082-.363.124q-.189.043-.382.043t-.382-.043t-.363-.124l-6.75-3.176q-.112-.053-.216-.121q-.103-.068-.196-.15t-.174-.176t-.147-.199t-.117-.218t-.086-.232t-.052-.241t-.017-.247V7.611q0-.124.017-.247q.018-.122.052-.241q.035-.119.086-.232t.117-.218t.147-.199t.174-.176t.196-.15t.216-.121l6.75-3.176q.175-.082.363-.124q.189-.042.382-.042t.382.042t.363.124l6.75 3.176q.112.053.216.121q.103.068.196.15t.174.176q.08.094.147.199t.117.218t.086.232t.052.241q.017.123.017.247v4.564");
}

</style>
