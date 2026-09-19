<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/m/mwjqgf-_o.css';
import '../../css/f/fi_moqbpl.css';
import '../../css/i/ixc_y2y0f.css';
import '../../css/i/i7_ys9b1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><rect class="mwjqgf-_o"/><path class="fi_moqbpl"/><circle class="ixc_y2y0f"/><path class="i7_ys9b1d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:radio-one" /></template>
