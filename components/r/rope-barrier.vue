<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjbji1b_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:rope-barrier" /></template>
<style>
.rjbji1b_a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 4q0-2.25 2.25-2.25T6.75 4q0 1.837-1.5 2.174v1.21Q6.977 12.75 12 12.75t6.75-5.366v-1.21q-1.5-.337-1.5-2.174q0-2.25 2.25-2.25T21.75 4q0 1.837-1.5 2.174v12.662q.877.241 1.337 1.159l.084.17q.359.718-.063 1.402q-.423.683-1.226.683h-1.764q-.803 0-1.226-.683q-.422-.684-.064-1.401l.086-.172q.459-.918 1.336-1.159v-7.969Q16.448 14.25 12 14.25t-6.75-3.384v7.97q.877.241 1.337 1.159l.084.17q.359.718-.063 1.402q-.423.683-1.226.683H3.618q-.803 0-1.226-.683q-.422-.684-.064-1.401l.086-.172q.459-.918 1.336-1.159V6.174Q2.25 5.837 2.25 4");
}

</style>
