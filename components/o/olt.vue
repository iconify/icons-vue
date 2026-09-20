<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fka69mbth"/><path class="vav5h16mw"/><path class="csms1vbyf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:olt" /></template>
<style>
.csms1vbyf {
  fill: var(--svg-color--008d9f, #008d9f);
  d: path("m16.218 12.563l3.653 2.109v4.219L16.218 21l-3.653-2.11v-4.218z");
}

.fka69mbth {
  fill: var(--svg-color--008d9f, #008d9f);
  d: path("m7.781 3l3.654 2.11v4.218l-3.654 2.11l-3.653-2.11V5.11z");
}

.ft5dv1b6b {
  fill: none;
}

.vav5h16mw {
  fill: var(--svg-color--00f1d0, #00f1d0);
  d: path("m7.781 12.563l3.654 2.109v4.218L7.78 21l-3.653-2.11v-4.218zM16.22 3l3.653 2.11v4.218l-3.653 2.11l-3.654-2.11V5.11z");
}

</style>
