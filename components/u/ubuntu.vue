<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="regwomb9a"/><circle class="zob0lqbpj"/><circle class="opv9_nbbn"/><path class="ujml_me-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ubuntu" /></template>
<style>
.opv9_nbbn {
  cx: 32.675px;
  cy: 38.576px;
  r: 6.109px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.regwomb9a {
  cx: 8.609px;
  cy: 22.82px;
  r: 6.109px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ujml_me-f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.239 36.052A17.35 17.35 0 0 0 43.084 24a17.34 17.34 0 0 0-3.975-11.074M8.969 28.918c2.122 7.22 8.798 12.492 16.706 12.492q.784 0 1.552-.069m1.295-34.519a17.5 17.5 0 0 0-2.833-.232h-.015c-6.075 0-11.424 3.113-14.539 7.83a17.4 17.4 0 0 0-1.33 2.408");
}

.zob0lqbpj {
  cx: 34.051px;
  cy: 9.424px;
  r: 6.109px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
