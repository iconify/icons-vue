<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g transform="scale(.99878)"><circle class="vpn2tp30j"/><path class="wb84h9bym"/><path class="ndvx3kbtf"/><path class="y0dihnllb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:three-oclock" /></template>
<style>
.ndvx3kbtf {
  fill: var(--svg-color--85939c, #85939c);
  d: path("M33.922 10.89c0-1.443-.85-2.609-1.893-2.609c-1.042 0-1.893 1.166-1.893 2.609V32c0 1.442.851 2.608 1.893 2.608s1.893-1.166 1.893-2.608z");
}

.vpn2tp30j {
  cx: 32.04px;
  cy: 32.04px;
  r: 29.68px;
  fill: var(--svg-color--e0e7ec, #e0e7ec);
}

.wb84h9bym {
  fill: var(--svg-color--98a9b4, #98a9b4);
  d: path("M0 32.04c0 17.666 14.372 32.04 32.04 32.04c17.666 0 32.04-14.372 32.04-32.04S49.706 0 32.04 0S0 14.372 0 32.04m6.237 0c0-14.228 11.575-25.803 25.801-25.803c14.228 0 25.803 11.575 25.803 25.803S46.266 57.843 32.038 57.843c-14.226 0-25.801-11.575-25.801-25.803");
}

.y0dihnllb {
  fill: var(--svg-color--788288, #788288);
  d: path("M48.02 34.77c1.438 0 2.607-.852 2.607-1.896c0-1.041-1.17-1.891-2.609-1.891l-15.276-.004c-1.438 0-2.607.851-2.605 1.891c-.002 1.044 1.167 1.896 2.6 1.896z");
}

</style>
