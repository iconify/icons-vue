<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="a5np3_q7m"/><path class="s_r8edbcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:ng-button" /></template>
<style>
.a5np3_q7m {
  fill: var(--svg-color--4fd1d9, #4fd1d9);
  d: path("M62 52c0 5.5-4.5 10-10 10H12C6.5 62 2 57.5 2 52V12C2 6.5 6.5 2 12 2h40c5.5 0 10 4.5 10 10z");
}

.s_r8edbcf {
  fill: var(--svg-color--fff, #fff);
  d: path("M44 42c-5.5 0-10-4.5-10-10s4.5-10 10-10c2.6 0 5 1 6.9 2.7l-2.3 2.4c-1.2-1.2-2.9-1.8-4.6-1.8a6.7 6.7 0 0 0 0 13.4c3.1 0 5.7-2.1 6.5-5H44v-3.3h10V32c0 5.5-4.5 10-10 10M26.7 22v14.3L12.4 22H10v20h3.3V27.7L27.6 42H30V22z");
}

</style>
