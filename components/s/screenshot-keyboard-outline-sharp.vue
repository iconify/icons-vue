<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqls66bee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:screenshot-keyboard-outline-sharp" /></template>
<style>
.cqls66bee {
  fill: currentColor;
  d: path("M11.996 14.5q-1.032 0-1.764-.735T9.5 11.996t.736-1.764t1.768-.732t1.764.736t.732 1.768t-.735 1.764t-1.769.732m2.483-.021Q15.5 13.458 15.5 12t-1.021-2.479T12 8.5T9.521 9.521T8.5 12t1.021 2.479T12 15.5t2.479-1.021M3 19V5h18v14zm1-1h16V6H4zm0 0V6z");
}

</style>
