<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/r-i1p99qp.css';
import '../../css/r/ry_lfzbyk.css';
import '../../css/a/atu28abtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="r-i1p99qp"/><path class="ry_lfzbyk"/><path class="atu28abtz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:translation" /></template>
