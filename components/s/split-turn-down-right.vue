<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/q/q9_aebbll.css';
import '../../css/y/yjnd42hik.css';
import '../../css/n/ndgf8g0be.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="q9_aebbll"/><circle transform="rotate(-90 13 8.944)" class="yjnd42hik"/><path class="ndgf8g0be"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:split-turn-down-right" /></template>
