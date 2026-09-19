<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/r7-1hnbno.css';
import '../../css/m/mhdh2_n-m.css';
import '../../css/n/n13p1fvkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="r7-1hnbno"/><path class="mhdh2_n-m"/><path class="n13p1fvkh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mushroom" /></template>
