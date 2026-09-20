<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="pgbx1yb0q"/><path class="zc--h_bjf"/><circle class="v30nwcctm"/><path class="gsi8jjnxr"/><path class="g1suawf9j"/><path class="vhby4ebkm"/><path class="ummj3fbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:woman-bowing-medium-skin-tone" /></template>
<style>
.g1suawf9j {
  fill: var(--svg-color--662113, #662113);
  d: path("M22 22a1 1 0 0 1-1-1v-1a1 1 0 1 1 2 0v1a1 1 0 0 1-1 1m-8 0a1 1 0 0 1-1-1v-1a1 1 0 1 1 2 0v1a1 1 0 0 1-1 1");
}

.gsi8jjnxr {
  fill: var(--svg-color--d5ab88, #d5ab88);
  d: path("M14 11s-.003 5.308-5 5.936V21c0 4.971 4.029 9 9 9s9-4.029 9-9v-3.019C15.89 17.605 14 11 14 11m3 23l-5-1l-2-1H7l-1 4h11c1 0 1-1 1-1c0-.553-1-1-1-1m9-2l-2 1l-5 1s-1 .447-1 1c0 0 0 1 1 1h11l-1-4z");
}

.pgbx1yb0q {
  fill: var(--svg-color--963b22, #963b22);
  d: path("M19 4c-1.721 0-3.343.406-4.793 1.111A7 7 0 0 0 13 5a7 7 0 0 0-7 7v12h.018C6.201 30.467 11.489 35.656 18 35.656S29.799 30.467 29.982 24H30v-9c0-6.075-4.925-11-11-11");
}

.ummj3fbjn {
  fill: var(--svg-color--5dadec, #5dadec);
  d: path("M5.499 8a1 1 0 0 1-.599-.2l-4-3a1 1 0 0 1 1.2-1.6l4 3A1 1 0 0 1 5.499 8m3.002-3a1 1 0 0 1-.833-.445l-2-3A1 1 0 0 1 7.332.445l2 3A1.001 1.001 0 0 1 8.501 5m22 3a1 1 0 0 1-.601-1.8l4-3a1 1 0 1 1 1.199 1.6l-4 3a1 1 0 0 1-.598.2m-3.002-3a1 1 0 0 1-.831-1.555l2-3a1 1 0 1 1 1.664 1.11l-2 3a1 1 0 0 1-.833.445");
}

.v30nwcctm {
  cx: 18px;
  cy: 28px;
  r: 3px;
  fill: var(--svg-color--cc9b7a, #cc9b7a);
}

.vhby4ebkm {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M19 26.5h-2a.5.5 0 0 1 0-1h2a.5.5 0 0 1 0 1");
}

.zc--h_bjf {
  fill: var(--svg-color--9268ca, #9268ca);
  d: path("M27 22H9s-9 0-9 7c0 3.156 4 7 4 7h28s4-3.844 4-7c0-7-9-7-9-7");
}

</style>
