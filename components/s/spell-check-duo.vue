<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vclaqt84l.css';
import '../../css/c/cx9tddlgw.css';
import '../../css/m/mika2zbzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="vclaqt84l wm-s"/><path class="cx9tddlgw"/><path class="mika2zbzn wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:spell-check-duo" /></template>
