<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/n/ninu-1bxu.css';
import '../../css/p/p3uy-bbpn.css';
import '../../css/s/sgxyf4b_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ninu-1bxu"/><path class="p3uy-bbpn"/><path class="sgxyf4b_g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:test-tube-01" /></template>
