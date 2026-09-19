<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle transform="rotate(-88.993 40.243 23.182)" class="gyl0msb5h"/><path class="eh5_7utrd"/><rect transform="rotate(-24.601 32.1 20.672)" class="vem0bb-vs"/><path class="q2ol6snhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:uno" /></template>
<style>
.eh5_7utrd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.032 11.801l3.876 8.464M22.004 31.136l-4.422-9.658l10.82 6.729l-4.422-9.658M8.39 25.687l2.958 6.459a3.519 3.519 0 1 0 6.398-2.93l-2.957-6.459");
}

.gyl0msb5h {
  cx: 40.243px;
  cy: 23.182px;
  r: 0.75px;
  fill: currentColor;
}

.q2ol6snhm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.692 15.468c1.228 2.643 1.229 5.63.22 8.586c-1.71 5.017-6.325 9.944-12.771 12.94c-10.244 4.762-21.234 2.844-24.547-4.283c-1.084-2.332-1.211-4.933-.533-7.544c1.393-5.368 6.192-10.778 13.084-13.982c6.692-3.11 13.702-3.37 18.682-1.19c2.644 1.157 4.717 3.002 5.865 5.473");
}

.vem0bb-vs {
  width: 7.037px;
  height: 10.622px;
  x: 28.582px;
  y: 15.361px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.519px;
  ry: 3.519px;
}

</style>
