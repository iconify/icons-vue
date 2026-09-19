<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p6r__lbdg"/><path class="hkwvt_bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:microsoft-authenticator-alt" /></template>
<style>
.hkwvt_bsw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 21.534a3.142 3.142 0 0 0-1.406 5.952a3.99 3.99 0 0 0-2.583 3.736h7.978a3.99 3.99 0 0 0-2.583-3.736A3.142 3.142 0 0 0 24 21.534");
}

.p6r__lbdg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.5c1.275 0 11.507-5.888 11.507-12.837V15.508C32.489 15.508 24 13.992 24 13.992s-8.496 1.516-11.507 1.516v15.155C12.493 37.613 22.725 43.5 24 43.5m8.014-30.618q.01-.178.012-.356a8.026 8.026 0 0 0-16.052 0q.002.178.012.356");
}

</style>
