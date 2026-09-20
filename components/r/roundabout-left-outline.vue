<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snpj3bnwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:roundabout-left-outline" /></template>
<style>
.snpj3bnwr {
  fill: currentColor;
  d: path("M14.98 20v-4.984q0-.552.36-.968t.912-.502q1.604-.269 2.676-1.449T20 9.307q0-1.784-1.261-3.045T15.673 5q-1.61 0-2.79 1.063t-1.449 2.666q-.086.552-.501.912q-.416.359-.967.359H4.92l2.1 2.1l-.713.708L3 9.5l3.308-3.308l.708.708L4.92 9h5.077q.154 0 .27-.115q.115-.116.153-.27q.331-1.988 1.797-3.302T15.673 4q2.212 0 3.77 1.548T21 9.308q0 1.988-1.323 3.445t-3.312 1.788q-.154.038-.269.163t-.115.279V20z");
}

</style>
