<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/w/wfx6i99th.css';
import '../../css/n/nkkh7xczj.css';
import '../../css/m/mo1bhs9ao.css';
import '../../css/i/iidcw5brz.css';
import '../../css/d/d03ao8bzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="wfx6i99th"/><path class="nkkh7xczj"/><path class="mo1bhs9ao"/><path class="iidcw5brz"/><path class="d03ao8bzs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:stopwatch-start" /></template>
