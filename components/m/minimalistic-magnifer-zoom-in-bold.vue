<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGSDTr4cZF"><g class="ft5dv1b6b"><path class="w9c06acrm"/><path clip-rule="evenodd" class="z0eul8k-i"/><path clip-rule="evenodd" class="nkv2sfb4k"/></g></mask></defs><path mask="url(#SVGSDTr4cZF)" class="w49j0rbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimalistic-magnifer-zoom-in-bold" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.nkv2sfb4k {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M18.838 18.838a.723.723 0 0 1 1.023 0l1.927 1.928a.723.723 0 0 1-1.022 1.022l-1.928-1.927a.723.723 0 0 1 0-1.023");
}

.w49j0rbvv {
  fill: currentColor;
  d: path("M0 0h24v24H0z");
}

.w9c06acrm {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.313 11.157a9.157 9.157 0 1 1-18.313 0a9.157 9.157 0 0 1 18.313 0");
}

.z0eul8k-i {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M11.157 8.024c.399 0 .723.324.723.723v1.687h1.686a.723.723 0 0 1 0 1.446H11.88v1.686a.723.723 0 1 1-1.445 0V11.88H8.747a.723.723 0 1 1 0-1.445h1.687V8.747c0-.4.323-.723.723-.723");
}

</style>
