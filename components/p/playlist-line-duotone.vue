<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ynnqgt8sp"/><path class="rhlnpmbpq"/><path class="vi7mzdtvt"/><path class="zbwqridka"/><path class="sqmdekbrs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:playlist-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rhlnpmbpq {
  d: path("M21 10L3 10");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.sqmdekbrs {
  d: path("M14.75 16.5C14.75 14.5904 14.75 13.6355 15.2858 13.1859C15.4199 13.0734 15.5725 12.9853 15.737 12.9254C16.3942 12.6862 17.2212 13.1636 18.875 14.1185C20.5288 15.0733 21.3558 15.5507 21.4772 16.2396C21.5076 16.4119 21.5076 16.5882 21.4772 16.7605C21.3558 17.4493 20.5288 17.9268 18.875 18.8816C17.2212 19.8365 16.3942 20.3139 15.737 20.0746C15.5725 20.0148 15.4199 19.9266 15.2858 19.8142C14.75 19.3646 14.75 18.4097 14.75 16.5Z");
}

.vi7mzdtvt {
  d: path("M11 14L3 14");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ynnqgt8sp {
  d: path("M21 6L3 6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.zbwqridka {
  d: path("M11 18H3");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
