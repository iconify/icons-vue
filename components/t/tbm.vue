<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qdo3gd-kw"/><path class="dxqn2cnpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tbm" /></template>
<style>
.dxqn2cnpg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.094 25.543c3.121-4.287 5.385-2.126 5.385-2.126c2.812 3.944-1.615 8.354-2.916 7.168c-2.266-2.067 6.155-14.31 9.775-13.719c2.421 1.506-2.833 7.865-1.372 9.02c1.872 1.499 4.82-7.696 7.27-6.482c2.897 2.037-4.952 9.19-1.714 11.524c2.175 1.1 3.978-2.161 3.978-2.161");
}

.qdo3gd-kw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.44 17.445l.04 13.037m7.291-6.604h3.693M4.5 17.444h15.964c3.44 0 3.84 6.133 0 6.441c3.827.751 3.498 6.582 0 6.582h-3.688v-13.02");
}

</style>
