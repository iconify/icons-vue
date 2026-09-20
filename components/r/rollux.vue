<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="sjh91lmgi"/><path class="l_xwihc7v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rollux" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l_xwihc7v {
  fill: var(--svg-color--000, #000);
  d: path("M8.024 7.353h.372l8.922 8.18v1.115H8.024zm7.036 5.396a3.717 3.717 0 0 0-5.278-4.838z");
}

.sjh91lmgi {
  fill: var(--svg-color--dbef88, #dbef88);
  d: path("M12 21a9 9 0 1 0 .001-18A9 9 0 0 0 12 21");
}

</style>
