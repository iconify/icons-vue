<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGbIX5GeZv"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="vsj_lac3a"/><path class="wuxvyy1ck"/><path class="xvsec-byc"/><path class="hl57-zb4i"/><path class="p-tfnibjf"/></g></mask></defs><circle mask="url(#SVGbIX5GeZv)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:shuffle-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.hl57-zb4i {
  d: path("M17.05 19.786a.75.75 0 0 1-.15-1.05l1.5-2a.75.75 0 1 1 1.2.9l-1.5 2a.75.75 0 0 1-1.05.15m2.41-11.564a.75.75 0 0 0-1.053.133l-1.5 1.936a.75.75 0 0 0 1.186.918l1.5-1.935a.75.75 0 0 0-.134-1.052");
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.kvn14gsjy {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
}

.p-tfnibjf {
  d: path("M17.05 6.15a.75.75 0 0 0-.15 1.05l1.5 2a.75.75 0 1 0 1.2-.9l-1.5-2a.75.75 0 0 0-1.05-.15");
}

.vsj_lac3a {
  d: path("M6 8.75a1 1 0 0 1 1-1c3.335 0 6.5 2.126 6.5 5.25s-3.165 5.25-6.5 5.25a1 1 0 1 1 0-2c2.74 0 4.5-1.68 4.5-3.25S9.74 9.75 7 9.75a1 1 0 0 1-1-1");
}

.wuxvyy1ck {
  d: path("M19 8.75a1 1 0 0 0-1-1c-3.335 0-6.5 2.126-6.5 5.25s3.165 5.25 6.5 5.25a1 1 0 1 0 0-2c-2.74 0-4.5-1.68-4.5-3.25s1.76-3.25 4.5-3.25a1 1 0 0 0 1-1");
}

.xvsec-byc {
  d: path("M19.46 17.778a.75.75 0 0 1-1.053-.133l-1.5-1.936a.75.75 0 0 1 1.186-.918l1.5 1.935a.75.75 0 0 1-.134 1.052");
}

</style>
