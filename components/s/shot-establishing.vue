<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="faqb5sghv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:shot-establishing" /></template>
<style>
.faqb5sghv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 5.25h12q1.76 0 3.005 1.245T22.25 9.5v5q0 .37-.055.718q-.065-.16-.193-.275q-5.304-4.774-10.607-.345q-4.697-2.313-9.355 1.31q-.026.02-.049.041q-.241-.674-.241-1.449v-5q0-1.76 1.245-3.005T6 5.25M2.727 17.215q.126.148.268.29Q4.24 18.75 6 18.75h12q1.76 0 3.005-1.245q.636-.636.947-1.407q-.051.039-.109.069t-.12.049t-.126.028t-.129.005q-.065-.002-.128-.016q-.064-.014-.124-.039q-.06-.024-.115-.059t-.103-.078q-4.498-4.048-8.996 0q-.044.039-.092.071q-.049.032-.102.056t-.11.039t-.114.022t-.116.004t-.115-.014t-.112-.031q-.054-.02-.105-.048q-4.067-2.26-8.176.936q-.105.082-.233.123M7.5 8q-2.25 0-2.25 2.25T7.5 12.5t2.25-2.25T7.5 8");
}

</style>
